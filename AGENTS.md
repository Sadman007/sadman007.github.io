# Repository Instructions

This is a minimal, custom-themed Jekyll blog.

## Architecture & Tech Stack
- **Framework:** Jekyll ~> 4.3 (Ruby).
- **Styling:** Vanilla CSS (`assets/css/main.css`). No preprocessors (no Sass, no Tailwind).
- **Theme:** None (`theme: null` in config). All layouts are custom and located in `_layouts/` and `_includes/`.

## Local Development
- **Install:** `bundle install`
- **Serve:** `bundle exec jekyll serve --livereload`
*(Note: There is no Node.js setup or `package.json`. Do not use npm/yarn commands).*

## Content Management
- **Posts:** Add to `_posts/` with the format `YYYY-MM-DD-title.md`. The permalink structure is configured as `/:categories/:title/`.
- **Pages:** Root markdown files (e.g., `index.md`, `about.md`) map to custom layouts in `_layouts/`.

## Writing & Style Rules
- **No Emojis:** Never use emojis in posts, UI elements, or code.
- **No Em-dashes:** Avoid using em-dashes (`—`) or hyphens used as dashes (` - `). Use semicolons, colons, or rewrite the sentence instead.
