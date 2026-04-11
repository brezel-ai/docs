# BrezelScraper documentation workspace

This directory contains the Mintlify docs project for BrezelScraper.

## What lives here

- Customer-facing guides in `index.mdx`, `quickstart.mdx`, and `guides/`
- Customer-facing API reference pages in `api-reference/`
- Contributor guidance in hidden MDX pages such as `development.mdx`, `essentials/`, and `ai-tools/`
- Site configuration in `docs.json`

## Source of truth

Use the application code to verify product behavior before you publish docs changes:

- Backend: `/Users/yasseen/Documents/brezel.ai/BrezelScraper/brezelscraper-backend`
- Frontend: `/Users/yasseen/Documents/brezel.ai/BrezelScraper/brezelscraper-frontend`

## Local development

```bash
npm i -g mint
mint dev
mint broken-links
```

## Contributor docs

- [Contributing guide](CONTRIBUTING.md)
- [Docs development](development.mdx)
- [Writing standards](essentials/markdown.mdx)
- [Navigation maintenance](essentials/navigation.mdx)
- [Reusable snippets](essentials/reusable-snippets.mdx)

## AI tooling

If you want Mintlify-specific component help in your editor or agent:

```bash
npx skills add https://mintlify.com/docs
```
