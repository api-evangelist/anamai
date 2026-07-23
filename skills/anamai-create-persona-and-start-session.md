---
name: Create a persona and start a live avatar session
description: Create an Anam persona, mint a session token, and start a live WebRTC persona session.
api: openapi/anamai-openapi-original.json
operations: [createPersona, createSessionToken, createEngineSession]
---

# Create a persona and start a live avatar session

Use this to stand up an Anam conversational AI avatar and bring it live.

## Auth
Anam uses a two-step Bearer model. Server-side calls send your API key as a Bearer
token. To connect a client, exchange the API key for a short-lived **session token**.
See `authentication/anamai-authentication.yml` and `conventions/anamai-conventions.yml`.

## Steps
1. **Create the persona** — `POST /v1/personas` (`createPersona`). Supply the name and,
   optionally, the `avatar`, `voice`, `llmId`, `brain`, and `tools` to attach. Capture the
   returned persona `id`.
2. **Mint a session token** — `POST /v1/auth/session-token` (`createSessionToken`) with the
   API key as Bearer auth. Returns a short-lived `SessionToken` for the client.
3. **Start the engine session** — `POST /v1/engine/session` (`createEngineSession`) to begin
   a live persona session (the client SDK then streams over WebRTC to a video element).

## Rules
- Never ship the API key to the browser — only the session token from step 2.
- Honor `RateLimit-Reset` / `Retry-After` on `429` (see `rate-limits/anamai-rate-limits.yml`).
- Concurrency is capped per plan (1–10 simultaneous sessions); check `GET /v1/sessions/concurrency`
  (`getSessionConcurrency`) before starting if you are near the limit.
- Errors are `application/json`; on `422` inspect field-level validation detail
  (`errors/anamai-problem-types.yml`).
