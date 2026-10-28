# Pharma Lab Global Italy — GitHub Pages

Six standalone research pages plus a Jekyll-powered blog and the original business logo.

## Deploy

Upload the entire **contents** of this folder to the repository **root**, preserving `_layouts/`, `_posts/`, and `blog/` folders. GitHub Pages: `main` / `/(root)` / Deploy from a branch. Do not upload the ZIP file itself. The site is built by GitHub Pages with Jekyll; no local build is required.

## Publish a new blog post

1. In GitHub repository select **Add file → Create new file**.
2. Use a filename such as `_posts/2026-10-29-new-research-topic.md` (YYYY-MM-DD-topic.md).
3. Paste the front matter and Markdown content below and commit on main. The filename date should match the publication date; future-dated posts may be hidden by Jekyll.
4. The new article appears automatically on `/blog/` after GitHub Pages builds.

```markdown
---
layout: post
title: "Your educational article title"
category: "Research Methods"
description: "A useful concise summary for search results."
---

Write an original article here with clear headings and scientific limitations.
```

Keep one natural external contextual product link if relevant to the article, and do not remove the automatic research-only disclaimer in `_layouts/default.html`. Links to other pages on this GitHub site are internal navigation, not product backlinks. Articles must be factual, educational, and not make human or animal treatment claims.

## Files

- `index.html`: standalone homepage with working blog links
- Five root peptide research HTML pages
- `_layouts/default.html`, `_layouts/post.html`: shared blog design
- `_posts/*.md`: Markdown article content
- `blog/index.html`: auto-generated blog listing
- `_config.yml`: GitHub Pages Jekyll settings
- `pharma-lab-global-logo.png`, `favicon.png`: local logo assets
- `robots.txt`, `sitemap.xml`: crawler guidance (blog sitemap entries may require later expansion or a sitemap plugin)
