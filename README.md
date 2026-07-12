# kolec94.github.io

This repository publishes the root GitHub Pages site for
`https://kolec94.github.io/`.

## Pages Entry Point

GitHub Pages is configured to publish from the `master` branch root. The root
homepage is `index.html`; keep that file as the canonical public entry point so
the site does not fall back to rendering this README through the default Jekyll
theme.

## Current Site Purpose

The homepage provides a lightweight project index with links to:

- The `kolec94` GitHub profile.
- The `tdongle-s3-hid` GitHub Pages site.
- Current public hardware, firmware, and operations-tooling repositories.

Old coursework chapter exports are intentionally not kept in this repository.
This repo is now scoped to the public profile landing page and direct supporting
assets only.

## Repository Layout

- `index.html` - root GitHub Pages homepage.
- `README.md` - repository documentation and maintenance notes.
- `assets/brand/` - AITOps-derived brand images used by the homepage.
- `tdongle/` - standalone project page assets for the T-Dongle S3 HID work.

Legacy root-level `.htm`, old CSS, unused images, tutorial assets, and temporary
text files are intentionally removed so the repository only contains current
Pages content.

## Validation

After changing the site, confirm that the Pages deployment succeeds and that
`https://kolec94.github.io/` serves the updated `index.html` content.
