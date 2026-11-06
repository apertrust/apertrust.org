# apertrust.org

Apertrust's website, an [Astro](https://astro.build) site published on GitHub Pages from `main` by `.github/workflows/deploy.yml`. The app itself lives in [apertrust/apertrust](https://github.com/apertrust/apertrust).

## Commands

```sh
npm ci
npm run dev
npm run build
```

## Rules

- Pages are in `src/pages/`; files served as they are (the logo, the favicon, `CNAME`) in `public/`. Keep `public/CNAME` as `apertrust.org`.
- Code is MIT ([LICENSE](LICENSE)); text and images are CC BY-SA 4.0 ([LICENSE-CONTENT](LICENSE-CONTENT)).
- Pin dependencies to exact versions and commit `package-lock.json`; pin every action by its commit SHA with the version in a comment.
- Write in British English, plainly. Never name commercial raw editors; say "commercial raw editors".
- Every commit carries a human's `Signed-off-by:` (`git commit -s`).
- Personal notes for this checkout go in `AGENTS.local.md`, which git ignores.
