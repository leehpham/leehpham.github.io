# Context Map: blog

_Last updated: 2026-10-20_

## Subdomains

| Subdomain | Type | Strategy | Why |
|---|---|---|---|
| Writing | Core | Build carefully | [Differentiator](../brief.md#strategy): "the writing is the core." Posts, front matter, tags, dates, slugs, drafts, publishing. Care goes into the posts and a strict post model, not the platform. |
| Reading | Supporting | Build simply | [Value proposition](../brief.md#strategy): "fast, clean, no blocking ads." Home, blog, post, tag and 404 pages; a [clean default theme](../brief.md#non-goals-for-now) is enough. |
| Author profile | Supporting | Build simply | [Problem](../brief.md#problem): a public portfolio and a brand for potential employers/clients. About page and contact links. |
| Agent access | Supporting | Build simply | [Differentiator](../brief.md#strategy) bonus: easy for AI agents to read. Raw Markdown and `llms.txt`; small and tied to our post model, so nothing worth buying. |
| Discovery | Generic | Buy | Readers [arrive from search or URLs](../brief.md#target-users). RSS feed, sitemap, SEO and social-preview tags are solved problems; use the official Astro integrations ([ADR-0001](../adr/0001_use_astro.md)). |
| Site generation | Generic | Buy | ["The platform is generic."](../brief.md#strategy) Markdown rendering, syntax highlighting and front-matter validation come with Astro ([ADR-0001](../adr/0001_use_astro.md)). |
| Hosting | Generic | Buy | [Business model](../brief.md#strategy): zero running cost; [live within 1 minute](../brief.md#success-metrics). GitHub Pages + Actions ([ADR-0002](../adr/0002_host_on_github_pages.md)). |
