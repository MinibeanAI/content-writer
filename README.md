# content-writer

A local-first Chinese article drafting skill. It turns a user-approved brief and source material into Markdown or an HTML preview.

The published workflow has no package installation, credential access, background tasks, online image generation, automatic search, or platform publishing. Read [SECURITY.md](SECURITY.md) for its capability boundary.

## Included references

- `prompts.md`: editable drafting prompts
- `reference/templates.md`: article structures
- `reference/styles.md`: local visual-style descriptions
- `examples/`: local style examples

## Optional extensions

The core skill can be published and used alone. Install an extension only when the user needs that capability:

- `extensions/content-writer-research`: approved online research and cited briefs
- `extensions/content-writer-images`: visual briefs and individually approved image requests
- `extensions/content-writer-delivery`: local files, remote documents, or publication after final confirmation
