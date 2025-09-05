# retiutut-personal-site

[![Deploy to GitHub Pages](https://github.com/retiutut/retiutut-personal-site/actions/workflows/deploy.yml/badge.svg)](https://github.com/retiutut/retiutut-personal-site/actions/workflows/deploy.yml)

This is a personal documentation and blog site built with [Docusaurus 3](https://docusaurus.io/), deployed to GitHub Pages at [docs.richardwaltman.com](https://docs.richardwaltman.com).

## Requirements

- Node.js >= 18 (tested with Node 20)
- Yarn (dependency management)

## Installation

```sh
yarn install
```

## Local Development

```sh
yarn start
```

This starts a local dev server. Most changes are reflected live without restart.

## Build

```sh
yarn build
```

Generates static content into the `build` directory.

## Deployment

Deployment is handled automatically via GitHub Actions on every push to `master`.

To deploy manually:

```sh
yarn deploy
```

This builds and pushes the site to the `gh-pages` branch for GitHub Pages hosting.

## Domain

The site is available at: https://richardwaltman.com

## Notes

- Dependency versions are managed with `yarn.lock` (do not use npm).
- No license file is present; all rights reserved unless otherwise stated.
