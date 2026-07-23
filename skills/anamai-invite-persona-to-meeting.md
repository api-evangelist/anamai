---
name: Invite a persona to a video meeting
description: Send an Anam persona into a Google Meet, Zoom, or Microsoft Teams call and manage the invite.
api: openapi/anamai-openapi-original.json
operations: [createPersona, createMeetingInvite, getMeetingInvite, cancelMeetingInvite]
---

# Invite a persona to a video meeting

Send a live Anam persona into a third-party video meeting via the Meetings API.

## Steps
1. **Have a persona** — reuse an existing persona `id` or create one with
   `POST /v1/personas` (`createPersona`).
2. **Create the invite** — `POST /v1/meetings/invites` (`createMeetingInvite`) with the
   meeting URL (Google Meet, Zoom, or Microsoft Teams), the persona config, and session
   options. Capture the invite `id`.
3. **Track join state** — `GET /v1/meetings/invites/{id}` (`getMeetingInvite`) to watch
   `status` / `joinState` as the persona joins.
4. **Cancel if needed** — `DELETE /v1/meetings/invites/{id}` (`cancelMeetingInvite`) to
   withdraw a pending invite.

## Rules
- The persona's display name carries an "(AI)" suffix with persistent AI-disclosure treatment
  on video — do not attempt to disguise the avatar as human.
- `422` returns validation detail (`MeetingInviteValidationError`); fix fields and retry.
- Honor rate-limit headers on `429`.
