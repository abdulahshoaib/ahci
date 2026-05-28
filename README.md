# AHCI

[![Netlify Status](https://api.netlify.com/api/v1/badges/22c6197b-4d47-462b-813e-c9d3f35246b8/deploy-status)](https://app.netlify.com/projects/ahci/deploys)

Hugo documentation site for AHCI course notes.

Course content lives in `content/docs`.

## Run Locally

```sh
hugo server
```

## Build

```sh
hugo --minify
```

## Deploy

Push to `main`. CI builds site, then promotes passing commits to `prod` for Netlify.
