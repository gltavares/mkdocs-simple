# Blocks

Zeroheight-style page blocks: split image and text, stacked media, rules, and tables. Write them as HTML in Markdown — no extra plugins.

## Two columns

Text beside a preview. Add `zh-split--flip` to put the image on the right. Stacks to one column on small screens.

<div class="zh-split">
  <div class="zh-media">
    <div class="zh-frame">
      <svg width="280" height="120" viewBox="0 0 280 120" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="24" y="36" width="112" height="40" rx="20" fill="currentColor"/>
        <text x="80" y="61" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="14" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Save changes</text>
        <rect x="148" y="36" width="92" height="40" rx="20" stroke="currentColor" stroke-width="1.5"/>
        <text x="194" y="61" text-anchor="middle" fill="currentColor" font-size="14" font-family="Inter, ui-sans-serif, sans-serif" font-weight="500">Cancel</text>
      </svg>
    </div>
  </div>
  <div class="zh-copy">
    <h3>Primary and secondary</h3>
    <p>Pair one filled action with a quiet alternative. The primary button is near-black (or near-white in dark mode); the secondary is outline-only.</p>
    <ul>
      <li>One primary per view</li>
      <li>Secondary for dismiss or back</li>
    </ul>
  </div>
</div>

<div class="zh-split zh-split--flip">
  <div class="zh-media">
    <div class="zh-frame">
      <svg width="280" height="132" viewBox="0 0 280 132" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="36" y="28" width="208" height="76" rx="10" stroke="currentColor" stroke-opacity="0.18" fill="var(--md-default-bg-color, #fff)"/>
        <rect x="52" y="44" width="88" height="10" rx="3" fill="currentColor" fill-opacity="0.18"/>
        <rect x="52" y="62" width="176" height="8" rx="3" fill="currentColor" fill-opacity="0.1"/>
        <rect x="52" y="76" width="140" height="8" rx="3" fill="currentColor" fill-opacity="0.1"/>
      </svg>
    </div>
  </div>
  <div class="zh-copy">
    <h3>Copy on the left</h3>
    <p>Use the flipped split when the writing is the point and the preview is supporting. Keep the media frame the same height as a sibling split so the page rhythm stays even.</p>
  </div>
</div>

## Image and text blocks

A full-width preview with a caption underneath — Zeroheight’s image block plus a paragraph.

<figure class="zh-block">
  <div class="zh-frame">
    <svg width="420" height="160" viewBox="0 0 420 160" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <rect x="28" y="36" width="364" height="88" rx="12" stroke="currentColor" stroke-opacity="0.16"/>
      <rect x="48" y="56" width="72" height="48" rx="8" fill="currentColor"/>
      <rect x="140" y="60" width="160" height="10" rx="3" fill="currentColor" fill-opacity="0.2"/>
      <rect x="140" y="80" width="220" height="8" rx="3" fill="currentColor" fill-opacity="0.1"/>
      <rect x="140" y="94" width="180" height="8" rx="3" fill="currentColor" fill-opacity="0.1"/>
    </svg>
  </div>
  <figcaption>
    <strong>Card anatomy</strong>
    Icon, title, and supporting line. Padding is 16px; the icon sits on the primary token so it holds in both palettes.
  </figcaption>
</figure>

Two of these side by side for before/after or variant shots:

<div class="zh-gallery">
  <figure class="zh-block">
    <div class="zh-frame">
      <svg width="200" height="88" viewBox="0 0 200 88" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="28" y="28" width="64" height="32" rx="16" fill="currentColor"/>
        <rect x="104" y="28" width="64" height="32" rx="16" stroke="currentColor" stroke-width="1.5"/>
      </svg>
    </div>
    <figcaption>
      <strong>Default</strong>
      Filled plus outline at 32px tall.
    </figcaption>
  </figure>
  <figure class="zh-block">
    <div class="zh-frame">
      <svg width="200" height="88" viewBox="0 0 200 88" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="40" y="32" width="52" height="24" rx="12" fill="currentColor"/>
        <rect x="104" y="32" width="52" height="24" rx="12" stroke="currentColor" stroke-width="1.5"/>
      </svg>
    </div>
    <figcaption>
      <strong>Compact</strong>
      Same pair at 24px for dense toolbars.
    </figcaption>
  </figure>
</div>

## Do / don’t

Rules blocks are the staple of a Zeroheight styleguide. Pair a preview with a short instruction.

<div class="zh-rules">
  <div class="zh-rule zh-rule--do">
    <div class="zh-frame">
      <svg width="220" height="72" viewBox="0 0 220 72" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="18" y="20" width="100" height="32" rx="16" fill="currentColor"/>
        <text x="68" y="41" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Save</text>
        <rect x="128" y="20" width="74" height="32" rx="16" stroke="currentColor" stroke-width="1.5"/>
        <text x="165" y="41" text-anchor="middle" fill="currentColor" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="500">Cancel</text>
      </svg>
    </div>
    <p class="zh-rule__label">Do</p>
    <p>Use one primary action and an outline secondary. The eye lands on Save first.</p>
  </div>
  <div class="zh-rule zh-rule--dont">
    <div class="zh-frame">
      <svg width="220" height="72" viewBox="0 0 220 72" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="18" y="20" width="90" height="32" rx="16" fill="currentColor"/>
        <text x="63" y="41" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Save</text>
        <rect x="118" y="20" width="84" height="32" rx="16" fill="currentColor"/>
        <text x="160" y="41" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Publish</text>
      </svg>
    </div>
    <p class="zh-rule__label">Don't</p>
    <p>Don’t place two filled primaries side by side. The actions compete and neither wins.</p>
  </div>
</div>

Add a caution when the rule is “it depends”:

<div class="zh-rules zh-rules--3">
  <div class="zh-rule zh-rule--do">
    <div class="zh-frame">
      <svg width="160" height="56" viewBox="0 0 160 56" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="24" y="12" width="112" height="32" rx="16" fill="currentColor"/>
        <text x="80" y="33" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Continue</text>
      </svg>
    </div>
    <p class="zh-rule__label">Do</p>
    <p>A single filled button is enough for a linear flow.</p>
  </div>
  <div class="zh-rule zh-rule--caution">
    <div class="zh-frame">
      <svg width="160" height="56" viewBox="0 0 160 56" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="18" y="12" width="124" height="32" rx="16" fill="oklch(0.577 0.245 27.325)"/>
        <text x="80" y="33" text-anchor="middle" fill="#fff" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Delete project</text>
      </svg>
    </div>
    <p class="zh-rule__label">Caution</p>
    <p>Destructive fill is reserved for confirm steps, not the first screen.</p>
  </div>
  <div class="zh-rule zh-rule--dont">
    <div class="zh-frame">
      <svg width="160" height="56" viewBox="0 0 160 56" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="8" y="12" width="64" height="32" rx="16" fill="oklch(0.577 0.245 27.325)"/>
        <rect x="80" y="12" width="72" height="32" rx="16" fill="currentColor"/>
      </svg>
    </div>
    <p class="zh-rule__label">Don't</p>
    <p>Don’t mix a red fill with a black fill in the same row.</p>
  </div>
</div>

## Tables

A property table for component APIs:

| Prop | Type | Default | Notes |
| --- | --- | --- | --- |
| `variant` | `primary` `secondary` `ghost` `destructive` | `primary` | One filled variant per row |
| `size` | `sm` `md` `lg` | `md` | Compact is 24px, default 32px |
| `disabled` | `boolean` | `false` | Keeps width; lowers contrast |
| `icon` | `left` `right` `only` | — | Icon-only needs an `aria-label` |

A borderless table for two-column copy, the way Zeroheight hides table chrome:

<table class="zh-layout">
  <tr>
    <td>
      <h3>When to use</h3>
      <p>Buttons start an action the user already understands. Prefer a button over a link when the result stays in the product.</p>
    </td>
    <td>
      <h3>When not to use</h3>
      <p>Navigation to another page is a link. Don’t style a link as a primary button just to make it louder.</p>
    </td>
  </tr>
</table>

See [Buttons](buttons.md) for these blocks used as a real styleguide page.

## Authoring

Copy the HTML from this page. Classes:

| Class | Role |
| --- | --- |
| `zh-split` | Two columns: media + copy |
| `zh-split--flip` | Image on the right |
| `zh-block` | Stacked preview + caption |
| `zh-gallery` | Two stacked blocks in a row |
| `zh-rules` | Do / don’t pair |
| `zh-rules--3` | Do / caution / don’t |
| `zh-rule--do` `zh-rule--dont` `zh-rule--caution` | Rule tone |
| `zh-layout` | Borderless layout table |
