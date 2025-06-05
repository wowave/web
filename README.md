# Haskell Homepage Skeleton

This repository contains a [Hakyll](https://jaspervdj.be/hakyll/) based static site
configured to work with GitHub Pages. The generated site lives in the `docs`
directory so it can be served directly from the `main` branch.

## Building locally

1. Install `ghc`, `cabal-install` and `hakyll` (already included in this
   repo's Docker environment).
2. Build and run the site generator:
   ```bash
   cd site
   cabal build
   cabal run site build
   ```
3. The HTML will be written to `../docs`.

You can enable GitHub Pages in your repository settings and choose the
`docs/` folder on the `main` branch as the source to publish the site.
