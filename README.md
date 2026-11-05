# Learn LMS Release Notes

Customer-facing release notes for Learn LMS, published with GitHub Pages: https://instrumentalgroup.github.io/learn-lms-release-notes

## Adding a release

Create `_posts/YYYY-MM-DD-release-X-Y-Z.md`:

```md
---
layout: post
title: "Release X.Y.Z"
date: YYYY-MM-DD
excerpt: "One-sentence summary."
---

## Theme modules
## Course pages and certificates
## Fixes
## Action required
```

Write for customers: no commit hashes, internal paths, portal IDs or customer names. Commit and push to `main`; Pages rebuilds automatically.

## Preview locally

```bash
bundle init && bundle add jekyll minima webrick
bundle exec jekyll serve
```
