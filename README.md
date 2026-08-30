# Sumit Chaurasia 👩🏻‍💻 — Portfolio

Single-file, static personal portfolio website. No build step, no dependencies to install — just open `index.html`.

## HyperLinks

- ℹ️LinkedIn: https://linkedin.com/in/sumitcr7
- 🐙GitHub: https://github.com/7sumitc
- 📧Email: mailto:7.sumitcr@google.com

## Structure

```
index.html    → Entire site (markup + styles + script, single file)
README.md     → Info file
```

## Sections

| Section    | Content                                                                 |
|------------|--------------------------------------------------------------------------|
| Hero       | Name, role, terminal-style intro card                                   |
| About      | Bio + stats (years experience, projects, events/day, uptime)            |
| Skills     | Python, SQL & Data Modeling, Apache Spark, Cloud & Infra                |
| Projects   | ETL/ELT Pipeline · Modeling & Warehousing · AI · Data Governance (Secoda)|
| Experience | BitTwoByte Technology (Data Engineer) · Hexaware Technology (Assoc. SWE)|
| Contact    | GitHub, LinkedIn, Email                                                  |

## Run locally

```bash
open index.html
# or
python3 -m http.server 8000
```

## Deploy

Drop `index.html` into any static host — GitHub Pages, Netlify, Vercel, S3 — no build required.

## Stack

- HTML5, CSS3 (custom properties, no framework)
- Vanilla JavaScript (IntersectionObserver for scroll reveals, scroll-spy nav)
- Google Fonts: Inter, JetBrains Mono

## Customize

- Colors/theme: CSS custom properties in `:root` (`--bg-deep`, `--accent`, `--accent-2`, etc.)
- Content: edit text directly inside the relevant `<section>` in `index.html`
- Contact links: update `href` values in the `#contact` section

## License

All rights reserved © Sumit Chaurasia, 2026.
