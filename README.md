# Hamp Developers

A 5-page team portfolio site built for **SWE2106 Internet Technologies and Web Design**,
Etivity 3. Hand-written HTML5, no frameworks, no external stylesheet.

Hamp Developers is a team of eleven Software Engineering students at Mbarara University of
Science and Technology (MUST).

## Pages

| Page | What's on it |
| --- | --- |
| `index.html` | Home. Semantic hub with `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>` |
| `about.html` | The team roster, an ordered list of team milestones, and a description list of technical terms |
| `gallery.html` | Media. Four `<figure>`/`<figcaption>` pairs plus an embedded demo video |
| `data.html` | Results. A skill proficiency table using `<thead>`, `<tbody>`, `<tfoot>` and `scope` |
| `contact.html` | Input. A contact form with native HTML5 validation |

## The team

| Name | Registration number |
| --- | --- |
| Wokwaba Charles | 2025/BSE/187/PS |
| Kanyesigye Brian | 2025/BSE/080/PS |
| Kwesiga Lewis | 2025/BSE/097/PS |
| Akatuwijuka Annibow | 2025/BSE/030/PS |
| Natweta Cyril | 2025/BSE/132/PS |
| Wawangula Generous | 2025/BSE/184/PS |
| Mugendawala Mark Paul | 2025/BSE/108/PS |
| Katto Andrew | 2025/BSE/085/PS |
| Nabaweesi Patricia Mirembe | — |
| Matovu Edwine Levi | — |
| Osuta Amen Joe | — |

Mark Paul Mugendawala is the team's lead developer and handles first contact — see `contact.html`.

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

## Version control

Built up in stages, one commit per page or feature. Run `git log --oneline` to see the sequence.

---

&copy; 2026 Hamp Developers
