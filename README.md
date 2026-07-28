# AI COO — Marketing Website

Commercial landing site for **AI COO**, the operating system for running a company.

## Design

A calm, professional aesthetic built on a **white and black** base with **gold‑yellow** accents.

- **Typography:** Fraunces (display serif) + Inter (body sans)
- **Palette:** near‑black ink `#131211`, warm off‑whites, gold `#c9a24b`
- Generous whitespace, hairline dividers, subtle reveal‑on‑scroll motion
- Fully responsive; respects `prefers-reduced-motion`

## Structure

```
index.html            # single-page site
assets/
  css/styles.css      # all styling (design tokens in :root)
  js/main.js          # nav, scroll reveal, demo form
```

Content is drawn from *AI COO — Vision v0.2*: the problem, solution, core
principles, Company Digital Twin, Company Skills, the Constraint Engine, a
supplier‑payment example, the three‑layer architecture, competitive
positioning, and the long‑term vision.

## Running locally

No build step — it's static HTML/CSS/JS.

```bash
# open directly
open index.html

# or serve it
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Notes

- The "Request a demo" form is front‑end only; wire it to your CRM or an
  endpoint of choice in `assets/js/main.js`.
- Fonts load from Google Fonts. Self‑host them if you need full offline use.
