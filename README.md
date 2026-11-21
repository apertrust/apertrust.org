# apertrust.org

Apertrust's website, [apertrust.org](https://apertrust.org), built with [Astro](https://astro.build) and published on GitHub Pages.

For now it is a placeholder in the website's colours and type: the logo, "See you soon", what Apertrust is, and a link to its source.

The custom error page in `src/pages/404.astro` builds to `dist/404.html`, which GitHub Pages serves for missing pages.

## Working on it

```sh
npm ci            # install the pinned dependencies
npm run dev       # a local server at http://localhost:4321
npm run build     # the site into dist/
```

Every push to `main` builds the site and publishes it (`.github/workflows/deploy.yml`).

## Licence

- The site's code is under the MIT licence ([LICENSE](LICENSE)).
- Its content, the text and images, is under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) ([LICENSE-CONTENT](LICENSE-CONTENT)).
- The fonts, Fraunces, DM Mono and Caveat, are under the SIL Open Font Licence 1.1, installed from Fontsource's packages and served with the site.
