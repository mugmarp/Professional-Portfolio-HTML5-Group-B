# Professional-Portfolio-HTML5-Group-B

A 5-page personal portfolio site built for **SWE2106 Internet Technologies and Web Design**,
Etivity 3. Hand-written HTML5, no frameworks, no external stylesheet.

## Pages

| Page | What's on it |
| --- | --- |
| `index.html` | Home. Semantic hub with `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>` |
| `about.html` | Bio. An ordered list of career milestones and a description list of technical terms |
| `gallery.html` | Media. Four `<figure>`/`<figcaption>` pairs plus an embedded demo video |
| `data.html` | Results. A skill proficiency table using `<thead>`, `<tbody>`, `<tfoot>` and `scope` |
| `contact.html` | Input. A contact form with native HTML5 validation |

## Folders

- `media/images/` — screenshots used on the gallery page, plus the social preview card
- `Design Documentation/` — sitemap and wireframes (Home and Gallery)

## Running it

No build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Accessibility notes

- Every page has a unique `<title>` and a `<meta name="description">`
- Every image has descriptive `alt` text that says what's in the picture, not the filename
- The table uses `scope="col"` and `scope="row"` so assistive tech announces the right header
- Colour pairs were checked against WCAG AA contrast ratios before being used
- Links are named for their destination — no "click here"

## SEO

- Per-page `<meta name="description">`, all under 160 characters
- Open Graph and Twitter card tags so pasted links render a preview card
- `sitemap.xml` and `robots.txt` at the repo root

## Version control

Built up in stages, one commit per page or feature. Run `git log --oneline` to see the sequence.

---

© 2026 Mark Paul Mugendawala
