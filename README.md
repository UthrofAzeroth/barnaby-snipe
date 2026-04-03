# Barnaby Snipe website

Static GitHub Pages website for the Barnaby Snipe pen name.

## Structure
- `index.html` — homepage
- `about/index.html` — about page
- `books/index.html` — books index
- `books/herb-aplenty/index.html` — current book page
- `privacy/index.html` — privacy page
- `style.css` — shared site styles
- `favicon.svg` — site icon
- `site.webmanifest` — web app manifest
- `robots.txt` — crawler instructions
- `sitemap.xml` — sitemap
- `humans.txt` — human-readable site metadata
- `llms.txt` / `llms-full.txt` — language-model-readable site summaries
- `404.html` — fallback page

## Existing repo asset
The cover image is intentionally **not** included here.
This build expects the repository already to contain:

`Herb Aplenty ebook cover.jpg`

in the repository root.

## Locked constraints
- no author photo
- no public contact page or contact details
- no newsletter or signup elements
- no hosted sample pages or teaser extracts

## Deployment
Upload these files into the `barnaby-snipe` repository root, leaving the existing cover JPG in place.

If you later use a custom domain, update canonical URLs, `sitemap.xml`, and `site.webmanifest`.