# Tooba Mir

Personal website: <https://toobamir.github.io>

Powered by [Jekyll](https://jekyllrb.com/) with the [al-folio](https://github.com/alshedivat/al-folio) theme.
Hosted by [GitHub Pages](https://pages.github.com/).

## Where to edit

| What | File |
| --- | --- |
| Name, site title, URL | `_config.yml` |
| Home page / bio | `_pages/about.md` |
| Profile photo | put it in `assets/img/`, then set `image:` in `_pages/about.md` |
| Publications | `_bibliography/papers.bib` |
| Projects | `_projects/*.md` |
| Teaching | `_teachings/*.md` |
| CV (page and generated PDF) | `_data/cv.yml` |
| Social links | `_data/socials.yml` |
| News items | add files to `_news/`, then set `announcements.enabled: true` in `_pages/about.md` |

## Local preview

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```
