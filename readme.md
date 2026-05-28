# hewage.io

Personal site of **Tharindu Hewage** — distributed systems engineer.
Minimal, data-driven [Jekyll](https://jekyllrb.com/) on GitHub Pages. No frameworks.

## How it's organised

Content is **data-driven** — to update the site you almost always edit a YAML
file in `_data/`, not HTML:

| File | Drives |
|------|--------|
| `_data/experience.yml`     | Work timeline (`/work/`) + resume |
| `_data/education.yml`      | Education (`/work/`) + resume |
| `_data/projects.yml`       | Projects (`/code/`); `featured: true` also shows on home |
| `_data/publications.yml`   | Publications (`/research/`) + resume |
| `_data/skills.yml`         | Skills (resume) |
| `_data/certifications.yml` | Awards & certifications (resume) — add as you earn them |

Layout/markup lives in `_layouts/` (`base`, `home`, `page`, `resume`); pages are
the thin `*.md`/`index.html` files at the root. All styling is one file:
`assets/css/main.css` (design tokens are the CSS variables at the top).

### Common edits
- **New job / project / paper / cert:** copy a block in the relevant `_data/*.yml`.
- **Nav item or social link:** edit `nav` / `profiles` in `_config.yml`.
- **Colours / fonts:** the `:root` variables in `assets/css/main.css`.

## Run locally

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

GitHub Pages builds `main` automatically on push. The custom domain is set in `CNAME`.

> Note: the **Resume** page is the source of truth; "download / print pdf" uses the
> browser's print-to-PDF via a dedicated print stylesheet (no PDF file to keep in sync).
