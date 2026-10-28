# Glossary (Ubiquitous Language)

_Last updated: 2026-10-25_

Bounded Contexts: see [context_map.md](./context_map.md).

**All** = same meaning in every context.

| Term           | Bounded Context | Definition                                                                                                                | Avoid                          |
|----------------|-----------------|---------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| About page     | Site            | The page at `/about` introducing the author, with contact links.                                                          | bio, contact page, profile     |
| AI agent       | Site            | Software that fetches posts on behalf of a person; served raw Markdown and `llms.txt`.                                    | bot, crawler, scraper          |
| Author         | Writing         | Me, Hoang Pham: the only person who writes and publishes posts.                                                           | admin, editor, owner, user     |
| Blog page      | Site            | The page at `/blog` listing every published post, newest first.                                                           | archive, posts page, feed      |
| Description    | Writing         | One sentence saying what a post is about; set in front matter and reused on the post page, RSS feed and social preview.   | summary, excerpt, subtitle     |
| Draft          | Writing         | A post that is not on `main` yet, so not published.                                                                       | WIP, unpublished post          |
| Front matter   | Writing         | The YAML block at the top of a post holding its title, description, dates and tags; invalid front matter fails the build. | header, metadata block         |
| Home page      | Site            | The site's landing page at `/`; not a list of posts.                                                                      | index, landing page            |
| `llms.txt`     | Site            | A Markdown file at the site root listing posts with links to their raw Markdown, per the llmstxt.org convention.          | —                              |
| Post           | Writing         | One piece of writing by the author, stored as a single Markdown file with front matter.                                   | article, entry, story          |
| Post page      | Site            | The page showing one post in full, at `/posts/<slug>`.                                                                    | article page, detail page      |
| Publish        | Writing         | Merge a post into `main`; the deploy that follows makes it live on the site.                                              | release, ship, deploy          |
| Published date | Writing         | The date a post was first published; never changes. Stored as `pubDate`.                                                  | created date, post date        |
| Raw Markdown   | Site            | The Markdown source of a post, served as plain text at its own URL.                                                       | source, plain-text version     |
| Reader         | Site            | A person reading the site: a developer, general reader, or potential employer/client.                                     | visitor, user, subscriber      |
| RSS feed       | Site            | The XML feed at `/rss.xml` that feed readers poll for new posts.                                                          | feed (alone), Atom, newsletter |
| Site           | Site            | The whole public website at https://leehpham.github.io.                                                                   | blog (alone), app, platform    |
| Slug           | Writing         | A post's URL-safe name, taken from its file name (`post-1` in `/posts/post-1`); never changes once published.             | permalink, handle              |
| Social preview | Site            | The card (title, description, image) shown when a post's URL is shared, built from Open Graph meta tags.                  | OG card, link preview, unfurl  |
| Tag            | Writing         | A lowercase label grouping posts by subject; a post has one or more.                                                      | category, label, topic         |
| Tag index      | Site            | The page at `/tags` listing every tag.                                                                                    | tags page, tag cloud           |
| Tag page       | Site            | The page at `/tags/<tag>` listing the posts with that tag.                                                                | category page, tag archive     |
| Updated date   | Writing         | The date of the last meaningful change to a published post; typo fixes don't count. Omitted if never updated.             | modified date, last edited     |
