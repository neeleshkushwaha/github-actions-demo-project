# GitHub Actions Demo Project (Node.js)

Small Dockerized Node.js demo to show CI (lint, test, build) and CD (build & push container).

Quick start

Run locally:

```bash
npm install
npm test
npm start
```

What’s included
- `app.js` - Express app
- `index.js` - server entry
- `test/app.test.js` - Jest + Supertest test
- `Dockerfile` - container image
- `.github/workflows/ci.yml` - CI workflow (lint, test, build)
- `.github/workflows/cd.yml` - CD workflow (push to GHCR on main/master)

Notes
- To push to GitHub Container Registry, the workflows use the repository `GITHUB_TOKEN` and `docker/build-push-action`.
- Adjust workflow branches and tagging to suit your repo.
# GitHub-Actions-Demo-Project

This repo will be used to setup demo project to implement CI/CD using GitHub Actions. 