# Material Shadcn

A Material for MkDocs overlay that reads like [mkdocs-shadcn](https://asiffer.github.io/mkdocs-shadcn/) — same quiet chrome, same oklch tokens — without installing that theme or any extra packages.

Drop `docs/stylesheets/extra.css` onto a Material site. That is the whole product.

The overlay remaps Material’s CSS variables to shadcn/ui neutrals, switches the type to Geist, and restyles Material’s own header, sidebar, search, admonitions, tabs, tables, and code. You keep Material’s components and structure. You do not get mkdocs-shadcn extensions such as Excalidraw, ECharts, or hover cards.

!!! note "What this is not"
    This is not a fork of mkdocs-shadcn and it does not vendor their Tailwind build. It is original CSS aimed at Material selectors, using the same public design tokens.

[Get started](getting-started.md){ .md-button .md-button--primary }
[Layouts](layouts/blocks.md){ .md-button }
