# Counterpart

Single-page marketing site for Counterpart, a Relationship Performance Advisory practice. Built as one static `index.html` file with no build step.

## Deploy (Vercel)

1. Push this folder to a GitHub repo.
2. In Vercel, import the repo. No framework, no build command, no output directory needed. It serves `index.html` as a static site.
3. Point the `counterpart.media` domain at the Vercel project in Project Settings > Domains.

`vercel.json` only enables clean URLs. Nothing else is required.

## Files

| File                    | Purpose                                                        |
|-------------------------|----------------------------------------------------------------|
| `index.html`            | The site (one file, no build step)                             |
| `logo.svg`              | Wordmark logo used in the hero                                 |
| `favicon.svg`           | Modern browser favicon (SVG, sharp at any size)                |
| `favicon-32.png`        | 32x32 PNG fallback                                             |
| `favicon.ico`           | Multi-resolution ICO for older browsers (16, 32, 48)           |
| `apple-touch-icon.png`  | 180x180 iOS bookmark icon                                      |
| `brian.jpg`             | Portrait used in the About section                             |
| `vercel.json`           | Clean URLs config                                              |

## Still to come

- Contact form: the `Contact Form Placeholder` div in the contact section is ready for the Tally embed snippet.

## Design tokens

| Token        | Value     | Use                       |
|--------------|-----------|---------------------------|
| Teal         | `#1F4E5F` | Primary accent            |
| Off-white    | `#F1F0EC` | Background                |
| Ink          | `#1A1A1A` | Body text, dark sections  |
| Bronze       | `#8C6A3F` | Secondary accent          |

Fonts load from Google Fonts: Inter (body) and Fraunces (headings).
