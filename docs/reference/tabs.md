# Tabs

Tabs are underline labels, not Material’s filled chips. The active label is foreground with a 2px bottom rule.

=== "pip"

    ```sh
    pip install mkdocs-material
    ```

=== "uv"

    ```sh
    uv add --dev mkdocs-material
    ```

=== "poetry"

    ```sh
    poetry add --group dev mkdocs-material
    ```

Content under the tabs can be prose as well as code.

=== "Overlay"

    One CSS file remaps tokens and restyles chrome. Keep it in `docs/stylesheets/extra.css` so Material can load it with `extra_css`.

=== "Theme fork"

    Forking Material or vendoring mkdocs-shadcn pulls in a template tree you then have to maintain. The overlay avoids that.

=== "Tailwind build"

    mkdocs-shadcn compiles Tailwind. This project does not. The look is close enough without a Node toolchain.
