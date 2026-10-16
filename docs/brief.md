# Project Brief: blog

_Last updated: 2026-10-04_

## Problem

I want to keep my writing habit going.

I need a public portfolio.

I want to learn and tinker with some new technologies.

I want to grow an audience and start building my branding.

I want a source of passive income.

## Target users

- **Me, as the author**: the primary user.
- **Developers**: arriving from search, or URLs;
  looking for solutions to specific problems.
- **General audience**: arriving from search, or URLs;
  looking for different views on specific matters.
- **Potential employers/clients**: checking my work and how I think.
- **AI Agents**: fetching post on behalf of their users;
  need content that's easy to parse.

Not for: anyone expecting a community or forum.

## Success metrics

- Site live on my own GitHub Pages by **2026-10-25**.
- **Under 1 minute** from "publishing" to the post being visible on the public site.
- Lighthouse (mobile) score **>= 95** for performance and
  accessibility and SEO, on the home page and a post page.
- Running cost **under $???/year**.
- **12 posts** published within 6 months of launch (about 2 posts/month).

## Scope (MVP)

- Posts written in Markdown and stored as Markdown.
- Published and updated dates on posts.
- A 404 page.
- Home page listing posts, newest first.
- Post pages with code syntax highlighting.
- Tags, with a page per tag.
- About page with contact links.
- RSS feed, sitemap, basic SEO and social-preview meta tags.
- Responsive layout that reads well on mobile.
- A raw Markdown version of each post, and an `llms.txt`.

## Non-goals (for now)

- Comments, newsletter, or site search.
- General-purpose CMS features: user roles, plugins, editorial workflows.
- Multiple authors.
- Monetization (ads, paywalls, sponsorships).
- A custom-designed theme; a clean, readable default is enough.

## Constraints

- 8 hours/day. 56 hours/week.

## Risks

- **Building the blog instead of writing on it.** This is the classic failure mode.
  _Mitigation:_ this is a personal pet project;
  learn-by-doing is part of the process so it's OK.

## Open questions

- Running cost per year is not determined yet.
  Once estimated, update "Success metrics" with this information.
- Budget is not determined yet.
  Once determined, update "Constraints" with this information.
- Hosting ??? (ADR note for this).
- Analytics ??? (ADR note for this).
- Domain name
