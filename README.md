# @reblackwell3/npm-publish-ci

Shared CI publish tooling for EndChess npm libraries: install deps (including `file:` → npm swap), build, dist fingerprint, auto patch-bump, publish, and push version commit.

## Usage

```bash
npx @reblackwell3/npm-publish-ci
```

Requires `NODE_AUTH_TOKEN` and `GITHUB_TOKEN` in CI.

Develop on **`dev`**, merge **`dev` → `main`** to publish (Publish workflow on push to `main`).
