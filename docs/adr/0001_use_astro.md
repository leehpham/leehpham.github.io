# ADR-0001: Use Astro as the static site generator

**Status:** Accepted

**Date:** 2026-10-17

## Context

Markdown posts must build into a fast static site with no servers.
Bad front matter must fail the build.

## Decision

We will use Astro with content collections and the official RSS and
sitemap integrations

## Consequences

### Positive
Front-matter validation and syntax highlighting come built in.

### Negative

Node dependencies need regular updates, and major upgrades
may need migration work, so the version is pinned.