# 七秒讀書會 · 7 Second Book Club

A personal reading notes site. Books I've read, ideas I don't want to forget — revisit in seven seconds.

🌐 **Live site:** https://kassielooo.github.io/7secondbookclub

---

## What's in this repo

```
7secondbookclub/
├── index.html        ← the whole website (single file)
├── logo.png          ← site logo
├── SlideFollow.png   ← shared follow slide shown at end of each book
└── slides/           ← all book slide images (PNG)
    ├── Bk01_...
    ├── Bk02_...
    └── Bk03_...
```

---

## Image naming convention

Slide filenames follow this pattern:

```
Bk[book number]_[post number]_[slide number]_[slide name].png
```

Example: `Bk01_2_03_Quote_2.png` = Book 01, Post 2, Slide 3, Quote 2

Post numbers:
- `1` — Book intro + key concepts
- `2` — Hook + quotes
- `3` — Lessons

---

## How to add a new book

**Step 1 — Add slide images**
Upload all new book PNGs into the `slides/` folder on GitHub.
Go to `slides/` → Add file → Upload files → commit.

**Step 2 — Update `index.html`**
Edit `index.html` and make three additions:

1. **Add the book name** to `BOOK_NAMES` array in the script
2. **Add the slide filenames** as a new array entry in `BOOKS`
3. **Add a book card** in the books grid HTML section

Follow the existing book entries as a template.

**Step 3 — Commit**
GitHub Pages updates automatically within ~1 minute.

---

## Built with

- HTML · CSS · vanilla JavaScript
- [Google Fonts](https://fonts.google.com/) — Space Grotesk + Noto Sans TC
- GitHub Pages for hosting

---

*Last updated: 2026-05-12*
