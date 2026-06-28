# Repository Guidelines

## Project Structure & Module Organization

This repository is a Jekyll site built on the Minimal Mistakes theme. Site configuration lives in `_config.yml`; root pages are in `_pages/`, dated content is in `_posts/`, and navigation/authors/UI labels are in `_data/`. Theme templates are split across `_layouts/` and `_includes/`, with Sass in `_sass/` and JavaScript, images, documents, and downloadable PDFs under `assets/`. The `docs/` directory contains upstream theme documentation and demo material. The `test/` directory is a fixture site used by the theme preview task.

## Build, Test, and Development Commands

- `bundle install`: install Ruby gems from the gemspec/Gemfile.
- `bundle exec jekyll serve`: run the main site locally, usually at `http://localhost:4000/`.
- `bundle exec jekyll build`: render the main site into `_site/`.
- `bundle exec rake preview`: serve the fixture site from `test/` at `/test/` while watching theme files.
- `bundle exec rake js`: rebuild `assets/js/main.min.js` with `uglify-js`.
- `bundle exec rake`: run the default maintenance tasks for copyright, changelog, JavaScript, and version files.

Do not commit generated `_site/` output unless the change explicitly requires it.

## Coding Style & Naming Conventions

Follow `.editorconfig`: 2-space indentation, LF line endings, UTF-8, trimmed trailing whitespace, and no forced final newline. Markdown may keep intentional trailing spaces. Use Jekyll front matter consistently and prefer lowercase, hyphenated filenames for posts and pages, such as `_posts/papers/2026-06-28-example-title.md`. Keep Liquid includes small and reusable; place broad layout behavior in `_layouts/` and page fragments in `_includes/`.

## Testing Guidelines

There is no standalone unit test suite. Validate changes by running `bundle exec jekyll build` for the main site and `bundle exec rake preview` for theme/layout changes. For content updates, check the affected page locally and confirm front matter, links, images, and downloadable assets resolve correctly. For JavaScript changes, rebuild with `bundle exec rake js` and verify the minified bundle changed as expected.

## Commit & Pull Request Guidelines

Recent history uses short descriptive subjects, sometimes in Portuguese, for example `Reset e padronização do site com Minimal Mistakes`. Keep commit subjects concise and action-oriented. Pull requests should state whether the change is a bug fix, enhancement, or documentation/content update; include a summary, related issue context when available, and screenshots for visible layout or styling changes.
