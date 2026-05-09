# Inference-Foundry.github.io

Public website for the **Inference Foundry** GitHub organization, hosted with [GitHub Pages](https://pages.github.com/) from this repository (`main` branch).

- **Live site:** [inference-foundry.github.io](https://inference-foundry.github.io/)
- **Branding:** Logo asset at `assets/images/inference-foundry-logo.jpg`

## Layout

| Path | Role |
|------|------|
| `index.html` | Single-page marketing site |
| `css/main.css` | Styles |
| `assets/images/` | Logo and static imagery |

## Homepage sections

- Hero, focus areas, projects
- Founders (with contact links and optional profile photos)
- Principles and contact call-to-action

## Founder image slots

The site is pre-wired with optional founder photos. Add images here:

- `assets/images/team/kritarth-dandapat.jpg`
- `assets/images/team/atshal-ahmed-khan.jpg`

If an image is missing, the page falls back to initials automatically.

## Local preview

From this directory, serve static files (Python example):

```bash
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080`.
