# Leonardo Oliveira – personal website

Academic website built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and hosted on GitHub Pages.

## Where to edit things

| What                         | File                          |
| ---------------------------- | ----------------------------- |
| Home page (bio, highlights)  | `_pages/about.md`             |
| Profile photo                | `assets/img/prof_pic.jpg`, then uncomment `image:` in `_pages/about.md` |
| Publications                 | `_bibliography/papers.bib`    |
| CV page                      | `_data/cv.yml`                |
| Projects                     | `_projects/*.md`              |
| Email, ORCID, LinkedIn, GitHub, Scholar | `_data/socials.yml` |
| Site name, URL, colours, features | `_config.yml`            |
| News items on the home page  | add files to `_news/`, then set `announcements: enabled: true` in `_pages/about.md` |

Every push to `main` rebuilds and publishes the site automatically (GitHub Actions, `.github/workflows/deploy.yml`).

Theme license: MIT (see `LICENSE`).
