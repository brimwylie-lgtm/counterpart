# Counterpart

Single-page marketing site for Counterpart, a Relationship Performance Advisory practice. Built as one static `index.html` file with no build step.

## Deploy (Vercel)

1. Push this folder to a GitHub repo.
2. In Vercel, import the repo. No framework, no build command, no output directory needed. It serves `index.html` as a static site.
3. Point the `counterpart.media` domain at the Vercel project in Project Settings > Domains.

`vercel.json` only enables clean URLs. Nothing else is required.

## Placeholders still to fill

- **Logo** — the `LOGO PLACEHOLDER` div in the hero. Drop in an `<img>` or inline SVG when the mark is ready.
- **Contact form** — the `CONTACT FORM PLACEHOLDER` div. Paste the Tally embed snippet there when you have it.

## Design tokens

| Token        | Value     | Use                |
|--------------|-----------|--------------------|
| Teal         | `#1F4E5F` | Primary accent     |
| Off-white    | `#F1F0EC` | Background         |
| Ink          | `#1A1A1A` | Body text / dark sections |
| Bronze       | `#8C6A3F` | Secondary accent   |

Fonts load from Google Fonts: Inter (body) and Fraunces (headings).
