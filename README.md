# personal-site

My personal website with some basic information about me.

[![Netlify Status](https://api.netlify.com/api/v1/badges/edeed704-072e-4864-88de-6a64e6031277/deploy-status)](https://app.netlify.com/sites/vibrant-beaver-8c9ce5/deploys)

## Stack

This site is a single, static `index.html` file with inline CSS and no framework/runtime dependencies.

## Netlify

This repo includes `netlify.toml` configured to avoid the common deploy error:

- `publish = "public"`
- Build command copies static files into `public/`

That means deploys succeed even if Netlify expects a `public` deploy directory.
