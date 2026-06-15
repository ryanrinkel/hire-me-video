# hire-me-video

Ryan Rinkel's video resume site, served via GitHub Pages at
`https://ryanrinkel.github.io/hire-me-video/`.

## Layout

| Path | What it is |
|------|------------|
| `index.html` | Main landing page (AI video → general resume). |
| `resume.html` | Default / general resume (linked from the main page). |
| `LTX_Director_*.mp4` | Background videos for the main landing page. |
| `r/_template/` | Template to copy for a new tailored version (Jekyll-hidden). |
| `r/<role>/` | One tailored version per role type (e.g. `r/sales/`). |

## Two kinds of visitors

- **Main page** (`/`): the AI video intro, with a button to the general resume.
- **Tailored link** (`/r/<role>/`): opens that role's resume **directly** — no
  video, no intermediate page. This is what you send when applying for a job.

## Tailored versions

Each version is a folder whose `index.html` **is** the tailored resume. Slugs are
role **types** (no company names), e.g.
`https://ryanrinkel.github.io/hire-me-video/r/sales/`.

### Add a new version

1. Copy `r/_template` → `r/<role>` (slug only, no leading underscore).
2. Overwrite `index.html` with your tailored resume export.
3. Commit & push, then send `…/hire-me-video/r/<role>/`.

See `r/_template/README.md` for the same checklist.
