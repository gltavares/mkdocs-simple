# Buttons

Buttons start an action. Keep one filled primary in a view, pair it with an outline secondary, and reserve red for confirm-and-destroy.

<div class="zh-split">
  <div class="zh-media">
    <div class="zh-frame">
      <svg width="300" height="140" viewBox="0 0 300 140" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="28" y="28" width="244" height="84" rx="12" stroke="currentColor" stroke-opacity="0.14"/>
        <rect x="48" y="54" width="116" height="32" rx="16" fill="currentColor"/>
        <text x="106" y="75" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Save changes</text>
        <rect x="176" y="54" width="76" height="32" rx="16" stroke="currentColor" stroke-width="1.5"/>
        <text x="214" y="75" text-anchor="middle" fill="currentColor" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="500">Cancel</text>
      </svg>
    </div>
  </div>
  <div class="zh-copy">
    <h3>When to use</h3>
    <p>Use a button when the person is committing to something on this screen: save, continue, apply, delete. If they are only moving to another page, use a text link.</p>
    <ul>
      <li>Labels are verbs: Save, Continue, Add filter</li>
      <li>Sentence case, no trailing punctuation</li>
      <li>Keep width hug-content; don’t stretch a single action to full bleed</li>
    </ul>
  </div>
</div>

## Hierarchy

Three weights are enough. Don’t invent a fourth fill just because a screen feels empty.

<figure class="zh-block">
  <div class="zh-frame">
    <svg width="440" height="88" viewBox="0 0 440 88" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <rect x="16" y="28" width="120" height="32" rx="16" fill="currentColor"/>
      <text x="76" y="49" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Primary</text>
      <rect x="152" y="28" width="120" height="32" rx="16" stroke="currentColor" stroke-width="1.5"/>
      <text x="212" y="49" text-anchor="middle" fill="currentColor" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="500">Secondary</text>
      <text x="348" y="49" text-anchor="middle" fill="currentColor" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="500">Ghost</text>
      <rect x="292" y="28" width="112" height="32" rx="16" fill="currentColor" fill-opacity="0.06"/>
    </svg>
  </div>
  <figcaption>
    <strong>Primary, secondary, ghost</strong>
    Primary is the one action you hope they take. Secondary cancels or goes back. Ghost sits in toolbars where a border would clutter the row.
  </figcaption>
</figure>

<div class="zh-gallery">
  <figure class="zh-block">
    <div class="zh-frame">
      <svg width="200" height="80" viewBox="0 0 200 80" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="24" y="24" width="72" height="32" rx="16" fill="currentColor"/>
        <rect x="108" y="28" width="64" height="24" rx="12" fill="currentColor"/>
      </svg>
    </div>
    <figcaption>
      <strong>Sizes</strong>
      Default 32px for forms and dialogs. Compact 24px for tables and toolbars.
    </figcaption>
  </figure>
  <figure class="zh-block">
    <div class="zh-frame">
      <svg width="200" height="80" viewBox="0 0 200 80" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="36" y="24" width="128" height="32" rx="16" fill="currentColor" fill-opacity="0.28"/>
        <text x="100" y="45" text-anchor="middle" fill="currentColor" fill-opacity="0.45" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Saving…</text>
      </svg>
    </div>
    <figcaption>
      <strong>Disabled and loading</strong>
      Don’t remove the button. Dim it and keep the label, or swap the label to a progress verb.
    </figcaption>
  </figure>
</div>

## Rules

<div class="zh-rules">
  <div class="zh-rule zh-rule--do">
    <div class="zh-frame">
      <svg width="230" height="72" viewBox="0 0 230 72" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="16" y="20" width="118" height="32" rx="16" fill="currentColor"/>
        <text x="75" y="41" text-anchor="middle" fill="var(--md-default-bg-color, #fff)" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Create project</text>
        <rect x="144" y="20" width="70" height="32" rx="16" stroke="currentColor" stroke-width="1.5"/>
        <text x="179" y="41" text-anchor="middle" fill="currentColor" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="500">Cancel</text>
      </svg>
    </div>
    <p class="zh-rule__label">Do</p>
    <p>Lead with the constructive action. Put Cancel second, as outline, never as another fill.</p>
  </div>
  <div class="zh-rule zh-rule--dont">
    <div class="zh-frame">
      <svg width="230" height="72" viewBox="0 0 230 72" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="12" y="20" width="64" height="32" rx="16" fill="currentColor"/>
        <rect x="84" y="20" width="64" height="32" rx="16" fill="currentColor"/>
        <rect x="156" y="20" width="62" height="32" rx="16" fill="currentColor"/>
      </svg>
    </div>
    <p class="zh-rule__label">Don't</p>
    <p>Don’t line up three filled buttons. If everything is primary, nothing is.</p>
  </div>
</div>

<div class="zh-rules">
  <div class="zh-rule zh-rule--do">
    <div class="zh-frame">
      <svg width="230" height="72" viewBox="0 0 230 72" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <text x="115" y="42" text-anchor="middle" fill="currentColor" font-size="14" font-family="Inter, ui-sans-serif, sans-serif" font-weight="500">View documentation →</text>
      </svg>
    </div>
    <p class="zh-rule__label">Do</p>
    <p>Use a text link for navigation. Underline is enough; don’t promote it to a primary button.</p>
  </div>
  <div class="zh-rule zh-rule--caution">
    <div class="zh-frame">
      <svg width="230" height="72" viewBox="0 0 230 72" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <rect x="44" y="20" width="142" height="32" rx="16" fill="oklch(0.577 0.245 27.325)"/>
        <text x="115" y="41" text-anchor="middle" fill="#fff" font-size="13" font-family="Inter, ui-sans-serif, sans-serif" font-weight="600">Delete project</text>
      </svg>
    </div>
    <p class="zh-rule__label">Caution</p>
    <p>A red fill is allowed on the confirm dialog, after the person has already chosen to delete.</p>
  </div>
</div>

## Content

<table class="zh-layout">
  <tr>
    <td>
      <h3>Labels</h3>
      <p>Start with a verb. Prefer Save changes over OK. Name the object when the screen has more than one possible save: Save draft, Save and publish.</p>
    </td>
    <td>
      <h3>Icons</h3>
      <p>An icon is optional on primary and secondary. Icon-only buttons need a visible tooltip and an accessible name. Don’t decorate Cancel.</p>
    </td>
  </tr>
</table>

## Properties

| Prop | Type | Default | Notes |
| --- | --- | --- | --- |
| `variant` | `primary` `secondary` `ghost` `destructive` | `primary` | One filled primary per region |
| `size` | `sm` `md` `lg` | `md` | 24 / 32 / 40px tall |
| `disabled` | `boolean` | `false` | Stays in layout; no pointer events |
| `loading` | `boolean` | `false` | Replaces the label with a progress verb |
| `icon` | `left` `right` `only` | — | `only` requires `aria-label` |
