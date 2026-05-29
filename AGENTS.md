# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub profile README** (`username/username` repo). It contains only a `README.md` file — no source code, no dependencies, no services.

### What this repo is

A static Markdown file displayed on the owner's GitHub profile page. There is no application to build or run.

### Development workflow

- **Lint**: `markdownlint README.md` (install via `npm install -g markdownlint-cli` if not present)
- **Preview**: `marked README.md` renders to HTML for visual verification (install via `npm install -g marked` if not present)
- **Test**: No automated tests exist. Validation = lint passes + rendered HTML looks correct.

### Notes for agents

- Do not attempt to install project dependencies — there are none.
- Changes to this repo are purely Markdown edits to `README.md`.
- The `preview.html` file in the repo root (if present) is a transient rendering artifact and should not be committed.
