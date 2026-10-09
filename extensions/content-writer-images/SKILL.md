---
name: content-writer-images
description: Prepare an image brief or coordinate a user-approved image-generation request for a specific article section. Use only when the user explicitly asks for visuals.
---

# Content Writer Images

This optional extension creates a visual plan. It can work with user-provided images, or with a user-approved image service through an already configured integration.

## Permission gate

Before requesting an image from a remote service, show and obtain approval for:

1. the service name;
2. the exact prompt, including article text that would be sent;
3. the selected section and number of images; and
4. the intended output location.

Do not ask the user to reveal keys or copy credentials into chat. Use an existing approved integration only after the user has authorized that request.

## Workflow

1. Ask the user to select a section, style, aspect ratio, and whether to use local or generated imagery.
2. Produce an image brief: subject, composition, palette, accessibility alt text, and rights note.
3. For local imagery, identify where the user should place the selected file; do not scan folders.
4. For a remote request, stop for approval immediately before transmitting the displayed prompt.
5. Return the selected image reference and alt text for the core writing skill.

## Boundaries

- Never generate images for every section by default.
- Never download arbitrary assets, edit third-party material, remove logos, marks, or attribution, or overwrite files.
- Do not publish images or attach them to an article automatically.
