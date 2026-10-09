---
name: content-writer-delivery
description: Prepare a reviewed article for a user-selected local file, document service, or publishing platform. Use only after the user explicitly asks for delivery.
---

# Content Writer Delivery

This optional extension handles delivery after the final article has been reviewed. It never decides where or whether to publish.

## Required confirmation

Before a write, copy, upload, or publication action, show and obtain confirmation of:

1. the final article version;
2. the exact target path, document, or platform account;
3. the audience or visibility where relevant; and
4. whether this is a draft, copy-only action, or public publication.

## Workflow

1. Default to returning a copy-ready Markdown or HTML block in chat.
2. For a local file, use only the explicitly named path and refuse to overwrite an existing file without a separate confirmation.
3. For a remote document, create or update only the document the user selected.
4. For a publishing platform, show a final preview and wait for the user’s approval immediately before the final submission.
5. Report the final destination and what was completed.

## Boundaries

- Do not inspect app data, credentials, prior drafts, contacts, or unrelated documents.
- Do not create scheduled posts, alter permissions, send notifications, or cross-post.
- Do not publish a draft merely because an earlier step produced it.
