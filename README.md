# Mach 2 Marketing Website

Jekyll-powered GitHub Pages site for **Mach 2 Marketing**.

## Local development (exact commands)

```bash
bundle install
bundle exec jekyll serve --livereload
```

Open: `http://127.0.0.1:4000`

## Build check

```bash
bundle exec jekyll build
```

## Notes
- Navigation links are data-driven in `_data/navigation.yml`.
- Shared structure lives in `_layouts/default.html` and `_includes/`.
- Page content lives in Markdown files with front matter.
