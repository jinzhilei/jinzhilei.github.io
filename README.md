# Lei Lab Website

Source code for the official website of the **Jinzhi Lei Research Group (雷锦志课题组)** at the School of Mathematical Sciences, Tiangong University.

**Live site:** https://jinzhilei.github.io

---

## Built With

- [Jekyll](https://jekyllrb.com/) — static site generator
- [al-folio](https://github.com/alshedivat/al-folio) — academic Jekyll theme
- [GitHub Pages](https://pages.github.com/) — free hosting

---

## Local Development

### Prerequisites

- Ruby ≥ 3.0
- Bundler: `gem install bundler`

### Setup

```bash
git clone https://github.com/jinzhilei/jinzhilei.github.io.git
cd jinzhilei.github.io
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

---

## How to Update the Site

### Add a News Post

Create a new file in `_posts/` following the naming convention `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Post Title"
date: 2026-01-01
categories: [Lab News, Talk]
---

Your post content in Markdown.
```

### Add a Team Member

Edit `_pages/members.md` and add a card block following the existing template.

### Update Publications

Edit `_pages/publications.md` and add a new entry under the appropriate year section.

### Update Research Directions

Edit `_pages/research.md`.

---

## Deployment

The site is automatically deployed to GitHub Pages whenever you push to the `main` branch, via the GitHub Actions workflow in `.github/workflows/deploy.yml`.

---

## License

Website content © Jinzhi Lei. Theme ([al-folio](https://github.com/alshedivat/al-folio)) licensed under MIT.
