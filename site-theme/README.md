# Moon repository-owned Astro theme

This directory is the repository-owned source of the site's Astro presentation layer.

- Original generator: yihong0618/isite
- Snapshot source commit: 123a35e42fcd68b3c128c59b9a38b6ba91219533
- Theme source of truth: this directory in the `myogg/moon` repository

The production and test workflows copy the files under `src/` into the generated `output/src/` after isite generates the site and before Astro builds. Edit the files here to change the site's presentation; do not edit generated files under `output/`.

Files deliberately left to isite generation because they provide content data, runtime behavior, or build configuration rather than the presentation layer:

- `src/content.config.ts`
- `src/lib/site.ts`
- `src/lib/urls.ts`
- `src/lib/image-optimizer.mjs`
- `src/pages/rss.xml.js`
- `package.json`, `astro.config.mjs`, `tsconfig.json`

Keeping those generated files preserves the existing content schema, site settings, URL handling, image optimization, RSS generation, and dependencies.
