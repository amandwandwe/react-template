# Changelog

All notable changes to this project will be documented in this file.

## [0.1.0] - 2026-08-21
- Initial commit: project scaffold
  - Added `package.json` with dependencies and dev tools
  - Added `index.html`, `src/main.jsx`, `src/router.jsx`
  - Added Tailwind setup via `src/main.css` and Vite plugin
  - Configured Vite in `vite.config.js`
  - Added `eslint.config.js` and project tooling
  - Added `LICENSE` (MIT)

## [0.1.1] - 2026-08-22
- Add Docker support and CI/CD workflows
  - Added `Dockerfile` for production image
  - Added `.dockerignore`
  - Added GitHub Actions: `ci-pipeline.yml`, `cd-pipeline.yml`, and `release-pipeline.yml`.
  - Updated documentation (`README.md`) with Docker and Pipelines notes
