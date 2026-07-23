---
name: Build a RAG knowledge base for a persona
description: Create a knowledge group, upload documents, and search it with vector similarity.
api: openapi/anamai-openapi-original.json
operations: [createKnowledgeGroup, uploadKnowledgeGroupDocument, listKnowledgeGroupDocuments, searchKnowledgeGroup]
---

# Build a RAG knowledge base for a persona

Ground an Anam persona in your own content using a knowledge (RAG) group.

## Steps
1. **Create the group** — `POST /v1/knowledge/groups` (`createKnowledgeGroup`). Capture the
   group `id`.
2. **Upload documents** — `POST /v1/knowledge/groups/{id}/documents`
   (`uploadKnowledgeGroupDocument`). Supports PDF, TXT, MD, DOCX, CSV up to 50MB. Auth can be
   the API key (Bearer) or an upload token (`X-Upload-Token` header).
3. **Confirm ingestion** — `GET /v1/knowledge/groups/{id}/documents`
   (`listKnowledgeGroupDocuments`); wait for each document `status` to finish processing.
4. **Search** — `POST /v1/knowledge/groups/{id}/search` (`searchKnowledgeGroup`) to retrieve
   similar content by vector similarity; attach the group to a persona's `knowledge` to ground it.

## Rules
- Large documents are processed asynchronously; poll document `status` before searching.
- Respect the 50MB per-file limit and supported file types.
- Honor rate-limit headers on `429`.
