# ADR-0002: Host on GitHub Pages, deployed by GitHub Actions

**Status:** Accepted

**Date:** 2026-10-17

## Context

The site is static and must cost nothing to run.
A post must be live within 1 minute of publishing.
The code already lives on GitHub.

## Decision

We will host on GitHub Pages and deploy with a GitHub Actions
workflow that builds the site with `withastro/action` on every
push to `main`.

## Consequences

### Positive

Hosting, HTTPS, and Actions minutes are free for a public repo,
with no extra account or secret to manage.

The workflow runs the real Astro build, so `dist/` is never
committed, unlike branch-based Pages publishing.

### Negative

We are tied to GitHub, can only serve static files, and must stay
within Pages' soft limits (1 GB site, 100 GB/month bandwidth).
