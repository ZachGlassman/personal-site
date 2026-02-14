# personal-site

My personal website with some basic information about me.

[![Netlify Status](https://api.netlify.com/api/v1/badges/edeed704-072e-4864-88de-6a64e6031277/deploy-status)](https://app.netlify.com/sites/vibrant-beaver-8c9ce5/deploys)

## Stack

This site is a single, static `index.html` file with inline CSS and no framework/runtime dependencies.

## Netlify

This repo includes `netlify.toml` configured for a plain static site:

- `publish = "."` (serve files from the repository root)
- `command = ""` (no build command)

If your Netlify UI still has an old build command (for example `hugo`), clear it in **Site settings → Build & deploy → Build settings** and redeploy.
