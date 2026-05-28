# AHCI Documentation

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
