# Some Thoughts

My personal blog built with [Hugo](https://gohugo.io/) and [PaperMod](https://github.com/adityatelange/hugo-PaperMod), deployed on GitHub Pages.

## How to Write a New Article

1. Create a new Markdown file in `content/posts/`:

```bash
hugo new content posts/my-new-article.md
```

2. Edit the file - fill in the front matter and write your content:

```markdown
---
title: "My New Article"
date: 2026-04-26
draft: false
tags: ["tech", "thoughts"]
summary: "A short summary that appears on the homepage."
---

Your article content goes here...
```

3. Commit and push:

```bash
git add .
git commit -m "Add new article: My New Article"
git push
```

4. GitHub Actions will automatically build and deploy your site.

## Local Preview

```bash
hugo server -D
```

Then open `http://localhost:1313` in your browser.

## Setup (First Time)

1. Create a repo named `osaamakhalil.github.io` on GitHub
2. Push this code to that repo
3. Go to **Settings > Pages** and set Source to **GitHub Actions**
4. Done - your site will be live at https://osaamakhalil.github.io
