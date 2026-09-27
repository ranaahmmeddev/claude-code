# SoCal sections for the Local theme (4.2.1)

Custom sections built on the Local theme's own typography, color, border and
spacing variables. Each section uses one accent color (default brand red
`#cf2122`; clear it to fall back to the theme accent).

## Install

Copy the files into the same folders of the theme (Online Store → Themes →
Edit code, or Shopify CLI):

| Folder | Files |
| --- | --- |
| `assets/` | `socal-sections.css` |
| `snippets/` | `socal-icon.liquid`, `socal-section-wrapper.liquid`, `socal-section-style.liquid`, `socal-section-background.liquid` |
| `sections/` | `socal-about-hero`, `socal-stats`, `socal-story`, `socal-statement`, `socal-cards`, `socal-partners`, `socal-cta`, `socal-faq`, `socal-delivery` (`.liquid`) |
| `templates/` | `page.about-socal.json` |

The sections also use the theme's own `lazy-image` snippet, which ships with Local.

## About page

1. Upload the files above.
2. Online Store → Pages → **About** → Theme template: **about-socal**.
3. Adjust text, images and blocks in the theme editor.

The template already points at images in the store's Files
(`the_woman.png`, the founder photo and four meal photos). The "Soup, curry
or stew" card has no photo yet. Add the Google reviews URL in the
**SoCal Call to action** section.

## Homepage

`socal-faq` and `socal-delivery` can be added to the homepage from the theme
editor (Add section → SoCal FAQ / SoCal Delivery Area). Their presets already
contain the FAQ answers, delivery towns/ZIPs and pickup locations.
