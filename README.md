# keniel123.github.io

Personal academic website of **Keniel Peart** — PhD researcher in AI at the University of Southampton (computer vision, 3D human motion modelling, radar sensing).

Built with [Jekyll](https://jekyllrb.com/) on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, hosted on GitHub Pages.

## Structure

| Path | Content |
| --- | --- |
| `_config.yml` | Site settings, author profile, sidebar links |
| `_pages/` | About (home), Research, CV, and the archive pages |
| `_publications/` | One Markdown file per publication |
| `_talks/` | One file per talk/demonstration |
| `_teaching/` | One file per teaching role |
| `_portfolio/` | One file per project (listed as "Projects") |
| `files/` | Downloadable CV PDF |
| `images/` | Profile photo and favicons |
| `_sass/theme/_mint_*.scss` | Site palette (customised to a sage green) |

## Local development

Requires Ruby ≥ 3.x and Bundler:

```bash
bundle install
bundle exec jekyll serve -l
```

Then open <http://localhost:4000>. GitHub Pages builds and deploys automatically on push to `master`.
