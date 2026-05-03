# Yu Zhu Personal Website

This repository contains the source for my academic personal website, built with Jekyll and the Academic Pages theme.

## Local Preview

Install Ruby/Bundler dependencies and serve the site:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

## Docker Preview

```bash
docker compose up
```

Then open <http://localhost:4000>.

## Common Maintenance

- Edit site-wide profile data in `_config.yml` and `_data/authors.yml`.
- Edit the homepage in `_pages/about.md`.
- Edit the markdown CV in `_pages/cv.md` and update the PDF at `files/cv.pdf`.
- Add publication entries under `_publications/`.
- Add project entries under `_portfolio/`.
- Run `scripts/update_cv_json.sh` only if the optional JSON CV page is re-enabled.
