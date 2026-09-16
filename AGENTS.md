# Repository Guidelines

## Project Structure & Module Organization

This repository is a Jekyll-based academic portfolio. Site content lives in `_pages/`, `_posts/`, `_news/`, `_books/`, and `projects/`; shared data and publication metadata are in `_data/` and `_bibliography/`. Presentation code is organized under `_layouts/`, `_includes/`, `_sass/`, and `_plugins/`. Put images, PDFs, fonts, notebooks, and other static files in `assets/`. Deployment and maintenance workflows are under `.github/workflows/`, with helper scripts in `bin/`.

## Build, Test, and Development Commands

- `bundle install` installs the Ruby/Jekyll dependencies.
- `bundle exec jekyll serve` runs the local site at `http://localhost:4000` with live rebuilding.
- `bundle exec jekyll build` generates the production site in `_site/`.
- `./bin/cibuild` runs the repository's CI build wrapper.
- `npx prettier . --check` checks formatting; use `npx prettier . --write` to apply it.
- `docker compose up` provides the documented containerized development environment.

## Coding Style & Naming Conventions

Use Markdown with YAML front matter for content and follow the existing Liquid, HTML, SCSS, JavaScript, and YAML patterns. Use two-space indentation where the surrounding file does not establish another style. Format supported files with Prettier; its Liquid plugin, 150-column width, and `trailingComma: "es5"` settings are defined in `.prettierrc`. Blog posts must use `YYYY-MM-DD-title.md` filenames, for example `_posts/2025-03-26-plotly.md`.

## Testing Guidelines

There is no unit-test suite. Before submitting changes, run a Jekyll build and the Prettier check, then inspect affected pages locally. CI also checks links for Markdown and HTML changes. The Axe accessibility workflow can be run manually when changing layouts, styling, or interactive behavior.

## Commit & Pull Request Guidelines

Recent commits use short, lowercase imperative summaries such as `update name` and `update new papers`; follow that concise style. For bugs and new features, open or reference an issue in the PR. Describe the affected pages or components, verification performed, and any configuration or content changes. Include screenshots for visual changes and confirm that formatting and the site build pass.
