# Johanna R. Thomson — research website

Academic research website built with Jekyll and hosted on GitHub Pages.

## View locally

The first time you work with the site, install its Ruby dependencies:

```bash
bundle config --local path vendor/bundle
bundle install
```

Then start the local preview:

```bash
bundle exec jekyll serve
```

Open:

<http://localhost:4000/johanna_thomson_hydroclimate/>

Stop the server with `Ctrl+C`.

Jekyll rebuilds the site when source files change. Refresh the browser to see
the updates. If port `35729` is available, you can instead use
`bundle exec jekyll serve --livereload` for automatic browser refresh.

## Site structure

- `index.md` — homepage
- `research.md` — research themes
- `publications.md` — selected publications
- `projects.md` — software, data, and reproducible materials
- `cv.md` — academic profile
- `contact.md` — contact details and research profiles
- `_layouts/default.html` — shared page layout and navigation
- `assets/css/style.scss` — site styling
- `_config.yml` — Jekyll and GitHub Pages configuration
