# example-percy-jekyll [![This project is using Percy.io for visual regression testing.](https://percy.io/static/images/percy-badge.svg)](https://percy.io/percy/example-percy-jeykll) [![CircleCI](https://circleci.com/gh/percy/example-percy-jekyll.svg?style=svg)](https://circleci.com/gh/percy/example-percy-jekyll)

Example app demonstrating Percy with a Jekyll created site.

To install dependencies, build and run the site:

    bundle install
    bundle exec jekyll build
    bundle exec jekyll serve
    open http://127.0.0.1:4000

To snapshot it in Percy, set your `PERCY_TOKEN` environment variable and then run:

    npx percy snapshot _site

### Attributions

Thank you to [CloudCannon](https://cloudcannon.com) for the [Hydra](https://github.com/CloudCannon/hydra-jekyll-template) theme.
