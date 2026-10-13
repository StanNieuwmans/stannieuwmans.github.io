# stannieuwmans.github.io

The websites for [Baken](https://github.com/StanNieuwmans/baken-ai), a personal assistant you own,
and [Dodo](https://github.com/StanNieuwmans/Dodo), a calm work layer on top of Azure DevOps.

Each is a static page with no build step: `public/baken/index.html`, served at
<https://stannieuwmans.github.io/baken/>, and `public/dodo/index.html` (English) plus
`public/dodo/nl/index.html` (Dutch), served at <https://stannieuwmans.github.io/dodo/>. Every push to `main` publishes
`public/` to GitHub Pages (`.github/workflows/pages.yml`). In the repository's Settings, Pages,
Source must be set to "GitHub Actions".
