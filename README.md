# React Template

Minimal React + Vite + Tailwind CSS starter template.

## Quick start

1. Install dependencies

```bash
npm install
```

2. Run the dev server

```bash
npm run dev
```

3. Lint the code

```bash
npm run lint
```

4. Build for production

```bash
npm run build
```

5. Preview the production build

```bash
npm run preview
```

## Docker

Build the Docker image (uses the provided `Dockerfile`):

```bash
docker build -t react-template:latest .
```

Run the container locally:

```bash
docker run -d --rm -p 80:80 --name react-template react-template:latest
```

A `.dockerignore` is included to keep the image small.

## CI / CD

This repo includes GitHub Actions workflows for CI and CD:

- `.github/workflows/ci-pipeline.yml` — runs tests, lint, and build on push/PR to `main`.
- `.github/workflows/cd-pipeline.yml` — example deployment pipeline that pulls and deploys a Docker image.

Adjust secrets and deployment steps to match your infrastructure.

## Project structure

- `index.html` — app entry HTML
- `src/main.jsx` — React entry file
- `src/main.css` — Tailwind CSS imports
- `src/router.jsx` — basic React Router setup
- `vite.config.js` — Vite configuration
- `eslint.config.js` — linting configuration
- `Dockerfile` — production image build
- `.dockerignore` — files excluded from Docker build
- `.github/workflows/` — CI/CD workflows

## Notes

- This template uses Vite and Tailwind CSS. Adjust `postcss.config` or Tailwind config as needed.
- See [LICENSE](LICENSE) for licensing information.
- Release history is in [CHANGELOG.md](CHANGELOG.md).

## Contributing

Feedback and PRs welcome. For CI changes, ensure workflows remain compatible with the repository's branch strategy.
