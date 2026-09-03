# Typography

Headings, body copy, lists, and quotes follow the shadcn docs scale: tight tracking, muted lead, and underlined links.

The paragraph immediately after an `h1` is treated as a lead. Use it for a one-line summary of the page, not a second heading.

## Section heading

Body text sits at about 15–16px with a relaxed line height. **Strong** is semibold, not extra-bold. [Inline links](../index.md) are underlined with an offset so they stay readable in a paragraph.

### Subsection

Use `h3` for named pieces inside a section. Keep titles short.

#### Fine print

`h4` is available when a subsection still needs a label. After that, prefer a bold lead-in on a paragraph.

## Lists

- Geist is self-hosted as a variable font
- Geist Mono is used for fences and chips
- No Google Fonts request leaves the page

1. Flatten the header
2. Remap the tokens
3. Restyle typeset surfaces

Nested lists stay compact:

- Navigation
    - Sidebar
    - Table of contents
- Content
    - Admonitions
    - Code fences

## Quote

> Documentation that also shines is usually just quieter chrome, not a new framework. The overlay keeps Material’s structure and changes the paint.

A keyboard hint looks like ++ctrl+k++ in running text. Inline `code` is a muted chip.

---

Horizontal rules are a single border token, not a Material gradient.
