# Contribute to the BrezelScraper docs

Use this repo to maintain the customer-facing BrezelScraper docs site and its supporting contributor guides.

## Workflow

1. Verify the product behavior in the backend or frontend first.
2. Update the relevant MDX page and `docs.json` if navigation changes.
3. Preview locally with `mint dev`.
4. Run `mint broken-links` before merging.

## Source of truth

- Backend: `/Users/yasseen/Documents/brezel.ai/BrezelScraper/brezelscraper-backend`
- Frontend: `/Users/yasseen/Documents/brezel.ai/BrezelScraper/brezelscraper-frontend`
- Contributor terminology and boundaries: `AGENTS.md`

## Contributor references

- [Docs development](development.mdx)
- [Writing standards](essentials/markdown.mdx)
- [API examples and code blocks](essentials/code.mdx)
- [Navigation maintenance](essentials/navigation.mdx)
- [Reusable snippets](essentials/reusable-snippets.mdx)

## Writing expectations

- Use the BrezelScraper terms `job`, `results`, `credits`, `dashboard`, and `integrations`
- Explain cost, runtime, or output tradeoffs when they affect user decisions
- Prefer verified examples over generic placeholders
- Remove starter boilerplate instead of leaving it hidden in the repo
