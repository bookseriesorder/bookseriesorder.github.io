# 📚 BookSeriesOrder

> **Never read a series out of order again.**  
> A free, fast, SEO-optimized reading order guide for the most popular authors — hosted on GitHub Pages.

🌐 **Live site:** <https://bookseriesorder.github.io>

-----

## 📖 Authors Covered

|Author           |Genre                 |Series                                |
|-----------------|----------------------|--------------------------------------|
|Colleen Hoover   |Romance / Contemporary|Slammed Series + Standalones          |
|Sarah J. Maas    |Fantasy / Romance     |ACOTAR, Throne of Glass, Crescent City|
|Rebecca Yarros   |Fantasy / Romance     |The Empyrean Series                   |
|Brandon Sanderson|Epic Fantasy          |Mistborn, Stormlight Archive          |
|James Patterson  |Thriller / Mystery    |Alex Cross Series                     |
|John Grisham     |Legal Thriller        |Jake Brigance Series + Standalones    |

-----

## ✨ Features

- ⚡ Loads in under 1 second — pure HTML & CSS
- 🔍 Fully SEO optimized — meta tags, Open Graph, Schema.org
- ❓ FAQ section with structured data for Google featured snippets
- 📱 Mobile responsive — works perfectly on any device
- 🔗 Amazon affiliate links on every book
- 🆓 Completely free — hosted on GitHub Pages forever
- 🗺️ Sitemap and robots.txt included

-----

## 🗂️ Files

```
bookseriesorder.github.io/
├── index.html       ← Main landing page
├── sitemap.xml      ← Google sitemap
├── robots.txt       ← Search engine instructions
└── README.md        ← This file
```

-----

## 🔧 How to Update

### Update the date (every 3–6 months)

Search for `2026-03-04` in `index.html` and replace with the current date.
Also update `sitemap.xml` with the new date.

### Add a new book

Find the author section in `index.html` and copy an existing book block:

```html
<div class="bitem">
  <div class="bnum">4</div>
  <div>
    <div class="btitle">New Book Title</div>
    <div class="byear">2026 · Description here</div>
  </div>
  <span class="bk bk-new">Latest</span>
</div>
```

### Add a new author page

Create a new folder with an `index.html` file:

```
/agatha-christie-books-in-order/index.html
/stephen-king-books-in-order/index.html
/jk-rowling-books-in-order/index.html
```

Then add the new URL to `sitemap.xml`.

-----

## 📈 SEO Strategy

- **Target keywords:** `[author name] books in order`, `reading order [series]`
- **Backlinks:** Reddit — r/books, r/Fantasy, r/RomanceBooks, r/suggestmeabook
- **Google Search Console:** Sitemap submitted at `sitemap.xml`
- **Update frequency:** Every 3–6 months or when new books release

-----

## 🗺️ Planned Author Pages

- [ ] Agatha Christie books in order
- [ ] Stephen King books in order
- [ ] JK Rowling books in order
- [ ] James Patterson books in order (full list)
- [ ] John Grisham books in order (full list)

-----

## 💰 Monetization

Amazon Affiliate links on every book title.  
Replace `YOURTAG-20` in `index.html` with your actual Amazon affiliate tag.

-----

## 📅 Changelog

|Date      |Update                               |
|----------|-------------------------------------|
|March 2026|Initial launch — 6 authors, 80+ books|

-----

*Built with pure HTML & CSS. Hosted free on GitHub Pages.*  
*Last updated: March 2026*
