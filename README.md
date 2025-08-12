<a href="https://jekyll-themes.com">
<img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield">
</a>

# [Start Bootstrap - Business Frontpage Jekyll Version](https://webjeda.com/business-frontpage/)

Source: [Start Bootstrap - Business Frontpage](https://startbootstrap.com/template-overviews/business-frontpage/)

## Copyright and License

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-business-frontpage/blob/gh-pages/LICENSE) license.

# MRV Notes

## Setup

    bundle config set --local path 'vendor/bundle'
    bundle install

## Serve locally

    bundle exec jekyll serve
    # Visit http://localhost:4000

## Build

    bundle exec jekyll build
    # Output in ./_site/

## Deploy to GitHub Pages

1. Commit and push changes:

        git add .
        git commit -m "update site"
        git push

2. In GitHub: **Settings → Pages**, select branch (`main`/`master`) and root folder (`/`).

## Notes

- `_config.yml` excludes `vendor/`, `.bundle/`, `node_modules/`, and build artifacts.
- Keep `Gemfile` + `Gemfile.lock` in repo to match GitHub Pages environment.
