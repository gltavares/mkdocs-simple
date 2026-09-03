# Admonitions

Admonitions render as rounded cards with a thin border. Color is used sparingly: muted by default, then blue, amber, red, or green when the tone actually matters.

!!! note "Note"
    Default callouts sit on the surface token. Use them for asides that should not compete with the heading.

!!! info "Info"
    Informational notes pick up a blue border and wash, close to the info cards on shadcn’s own docs.

!!! tip "Tip"
    Tips and success states share the emerald treatment.

!!! success "Success"
    The overlay applied. Light and dark both read as cards, not as Material’s left-bar callouts.

!!! warning "Warning"
    Warnings use the shadcn warning oklch, not Material’s deep orange bar.

!!! danger "Danger"
    Destructive callouts keep a red border and a light wash so they stay visible without filling the column.

Collapsible details use the same card:

??? question "What did we leave out?"
    mkdocs-shadcn’s custom admonition plugins and Iconify titles. Material’s built-in types are enough for a docs gallery.

Inline `code` inside a callout keeps a light border so it does not disappear into the wash.
