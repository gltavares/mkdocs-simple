# Tables

Tables are bordered, slightly rounded, and quiet. Header cells use the muted surface; hover tints a row without a heavy Material stripe.

| Piece | Material default | Overlay |
| --- | --- | --- |
| Header | Indigo bar | Page background, 1px border |
| Primary color | `#4051b5` | Near-black / near-white |
| Sidebar labels | Uppercase, tracked | Sentence case, semibold |
| Admonitions | Colored left bar | Rounded card |
| Tabs | Filled chips | Underline labels |
| Code | Squared, busy shadow | `rounded-xl` muted surface |
| Fonts | Roboto from Google | Self-hosted Inter |

Alignment still works:

| Token | Light | Dark |
| ---: | :---: | :---: |
| `--background` | `oklch(1 0 0)` | `oklch(0.145 0 0)` |
| `--foreground` | `oklch(0.145 0 0)` | `oklch(0.985 0 0)` |
| `--border` | `oklch(0.922 0 0)` | `oklch(1 0 0 / 10%)` |
| `--radius` | `0.625rem` | `0.625rem` |

A table with inline `code` should keep chips readable on both the header and body rows.

Borderless two-column copy (Zeroheight’s “hide table borders” trick) lives on [Blocks](../layouts/blocks.md) as `table.zh-layout`.
