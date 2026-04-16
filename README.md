# Trupeer Documentation

Source for the Trupeer documentation site — guides, reference material, and assets.

## Structure

```
.
├── docs.json              # Mintlify configuration
├── index.mdx              # Documentation landing page
├── docs/
│   └── getting-started.mdx
├── guides/                # Feature guides (with images)
├── reference/             # Text-only reference material
└── images/                # Screenshots referenced from guides
```

## Local Development

```bash
npm install
npm run dev
```

The site will be available at `http://localhost:3000`.

## Deployment

```bash
npm run deploy
```

## Editorial Conventions

- Use sentence case in body copy; title case in headings
- Reference surfaces with the canonical name (e.g., "Knowledge Base," not "knowledge base")
- Embed images inside `<Frame caption="...">` components for consistency
- Cross-link related guides using relative paths (`/guides/...`, `/reference/...`)
