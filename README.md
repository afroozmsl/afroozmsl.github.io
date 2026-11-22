# Afrooz Mosallaei's website

Personal research website for Afrooz Mosallaei, built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme. GitHub Actions builds and deploys the site from the `main` or `master` branch.

## Content

| File | Public URL |
| --- | --- |
| `_pages/index.md` | `/` |
| `_pages/selected-projects.md` | `/selected-projects/` |
| `_pages/publications.md` | `/publications/` |
| `_pages/invited-contributions.md` | `/invited-contributions/` |
| `_pages/teaching.md` | `/teaching/` |
| `_pages/cv.md` | `/cv/` |

`_pages/research.md` and `_pages/service.md` retain the previous URLs as redirects. The CV PDF is at `assets/pdf/cv.pdf`; it needs a content update before being featured again. The profile photo is at `assets/img/Mosallaei_ProfilePic.jpg`. Site settings and navigation order are in `_config.yml` and the pages' front matter. The editorial style adjustments are in `_sass/_editorial.scss`.

## Run locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`. Deployment runs through `.github/workflows/deploy.yml`.
