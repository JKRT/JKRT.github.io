# jkrt.github.io

Source of John Tinnerholm's personal website, https://jkrt.github.io.

Built by GitHub Pages (deploy from branch `master`) with Jekyll and the
[Academic Pages](https://github.com/academicpages/academicpages.github.io) template, a fork of Minimal Mistakes.

## Theme

The theme files (`_includes/`, `_layouts/`, `_sass/`, `assets/`, `_data/ui-text.yml`, favicons in `images/`)
are copied from Academic Pages upstream commit `3d28cd2` (2026-09-18). To update the theme, copy those again
from upstream and reapply these local changes:

- `_includes/footer.html`: 🤖 link to `/agents/` after the sitemap link
- `_includes/head/custom.html`: comment and `<link rel="alternate">` pointing agents to `/llms.txt`
- `_includes/footer/custom.html`: MathJax removed (no math on the site)
- `_sass/layout/_sidebar.scss`: sidebar `li` uses `white-space: normal` so long lines wrap

Colour theme: `site_theme` in `_config.yml`; visitors can switch light/dark with the toggle in the menu.

## Content

- `_pages/`: About (`about.md`), Publications, Talks, Teaching, Software, CV, AGENTS
- `_data/navigation.yml`: top menu
- `_config.yml`: site settings and the sidebar profile (`author:`)

## Local preview

Needs Ruby 3.3 (`github-pages` does not support Ruby 4.0) and a UTF-8 locale.

```bash
export PATH=/opt/homebrew/opt/ruby@3.3/bin:$PATH LANG=en_US.UTF-8
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Then open http://localhost:4000.
