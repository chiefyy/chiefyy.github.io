# Lennart Schultz — personal website

Jekyll website for GitHub Pages. Existing WordPress homepage, images and CV migrated; empty About and Works pages retained. Contact email removed at the owner's request.

## Add a post

Create `_posts/YYYY-MM-DD-title.md` through GitHub → Add file → Create new file:

```markdown
---
title: Your title
categories: [essays]
---

Your text here.
```

Categories: `essays`, `poetry`, `photography`, `composition`.
Upload photos to `assets/images/`, then include `![Description](/assets/images/filename.jpg)`.
Committing to main automatically rebuilds the site after Pages is enabled.

No custom domain is configured yet. The WordPress XML export is deliberately excluded from this public repository.
