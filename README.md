# Material Shadcn

A [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) overlay that reads like [mkdocs-shadcn](https://asiffer.github.io/mkdocs-shadcn/). One CSS file. No extra Python packages, no Tailwind, no Google Fonts.

## Run locally

```sh
pip install -r requirements.txt
mkdocs serve -a 127.0.0.1:43147
```

Open [http://127.0.0.1:43147/](http://127.0.0.1:43147/).

Clone this repo:

```sh
git clone https://github.com/gltavares/mkdocs-toranja.git
```

## Reuse in another Material site

1. Copy [`docs/stylesheets/extra.css`](docs/stylesheets/extra.css).
2. Copy [`docs/assets/fonts/`](docs/assets/fonts/) (Geist, SIL OFL).
3. Copy [`overrides/`](overrides/) for the header and search chrome.
4. Set `theme.custom_dir: overrides`, `theme.font: false`, `primary`/`accent: custom`, and `extra_css: [stylesheets/extra.css]`.

The overlay remaps Material CSS variables to shadcn/ui oklch tokens, uses Geist, and restyles Material’s own header, sidebar, search, admonitions, tabs, tables, and code. Layout blocks on [Layouts](docs/layouts/blocks.md) cover split image+text, media, do/don’t, and tables. It does not add Excalidraw, ECharts, KaTeX, or other mkdocs-shadcn plugins.

## License

Project code is yours to reuse in this repository. Geist is licensed under the [SIL Open Font License](docs/assets/fonts/OFL.txt). Design tokens follow the public shadcn/ui palette used by mkdocs-shadcn (MIT).
