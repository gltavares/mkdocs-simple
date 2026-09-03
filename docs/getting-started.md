# Getting started

Install Material for MkDocs, copy one stylesheet, and turn off Google Fonts. Nothing else is required.

## Install

```sh
pip install mkdocs-material
```

Or pin the version this repo was built against:

```
mkdocs-material==9.7.7
```

## Wire it up

Copy `docs/stylesheets/extra.css` and the Geist files in `docs/assets/fonts/` into your project, then point Material at them. Also copy `overrides/` if you want the shadcn header and search chrome.

```yaml
theme:
  name: material
  custom_dir: overrides
  font: false
  palette:
    - scheme: default
      primary: custom
      accent: custom
      toggle:
        icon: material/weather-night
        name: Switch to dark mode
    - scheme: slate
      primary: custom
      accent: custom
      toggle:
        icon: material/weather-sunny
        name: Switch to light mode
  features:
    - navigation.tabs
    - navigation.sections
    - navigation.footer
    - toc.follow
    - search.suggest
    - content.code.copy
    - content.tabs.link

extra_css:
  - stylesheets/extra.css
```

`font: false` stops Material from loading Roboto from Google Fonts. The overlay self-hosts Geist and Geist Mono — the shadcn/ui stack — instead.

## Run

```sh
mkdocs serve -a 127.0.0.1:43147
```

## What you get

- Neutral oklch palette for light and dark, not indigo/teal
- Sticky header on the page background with a 1px border
- Header tabs that filter the sidebar to the active section
- Compact sidebar with sentence-case section labels
- Search field that looks like a shadcn input
- Card-like admonitions, underline tabs, rounded code blocks
- Zeroheight-style splits, media blocks, do/don’t rules, and layout tables

## What you do not get

mkdocs-shadcn ships plugins and Markdown extensions this overlay does not: stargazers, copy-page, KaTeX, ECharts, Excalidraw, Iconify, and hover cards. Material’s built-in search, admonitions, tabs, and code copy cover the docs chrome.

!!! tip "Reuse"
    Prefer patching `extra.css` over forking Material. The optional `overrides/` files only reorder the header and search placeholder.
