---
version: alpha
name: EastMesh
description: Community MeshCore / LoRa connectivity for Australia, expressed through a dark technical canvas, living green signal, and cool network blues.
colors:
  primary: "#267342"
  ink: "#222222"
  surface: "#303030"
  surface-soft: "#343434"
  text: "#E6EAF0"
  muted: "#9AA4B2"
  green: "#36A167"
  green-light: "#267342"
  green-deep: "#224C36"
  blue: "#1E3A5F"
  blue-electric: "#2563EB"
  cyan: "#06B6D4"
  lime: "#B7F21D"
  white: "#FFFFFF"
typography:
  display:
    fontFamily: Inter
    fontSize: 2.4rem
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.025em"
  heading:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: 600
    lineHeight: 1.25
  body:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0.14em"
  code:
    fontFamily: "JetBrains Mono"
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.5
rounded:
  sm: 10px
  md: 14px
  pill: 999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 36px
  xxl: 48px
components:
  button-primary:
    backgroundColor: "{colors.green-light}"
    textColor: "{colors.white}"
    rounded: "{rounded.pill}"
    padding: "9px 15px"
  button-primary-hover:
    backgroundColor: "#287A43"
    textColor: "{colors.white}"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: "24px"
  code-block:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    padding: "14px"
---

## Overview

EastMesh is a community-built, Australia-focused MeshCore / LoRa network. The visual identity should feel **technical, useful, local, and alive**: a calm dark interface with a clear green signal, backed by blue radio/network energy.

Use the identity consistently across eastmesh.au, maps, dashboards, documentation, printed promotion, stickers, and firmware displays such as the CYD notifier.

### Brand character

- **Connected:** signals, nodes, routes, and people are visibly linked.
- **Practical:** explain what something does before decorating it.
- **Community-run:** human, open, and approachable rather than corporate.
- **Australian:** use the Australia mark and regional language where useful, without turning the brand into a flag motif.
- **Technical but calm:** precision and legibility beat cyberpunk effects.

### Core phrase

**Community mesh. Local signal.**

Supporting language: **Community-run MeshCore / LoRa network.**

## Colors

### Core palette

- **Graphite / Ink `#222222`:** default dark canvas. Use for page backgrounds and firmware dark mode.
- **Surface `#303030`:** cards, navigation, panels, and raised content.
- **Surface Soft `#343434`:** code blocks, inset areas, and secondary controls.
- **Signal Green `#36A167`:** primary action, active state, online indicator, and brand energy.
- **Light-mode Green `#2F8F4E`:** accessible light-surface accent.
- **Text `#E6EAF0`:** primary dark-mode text.
- **Muted `#9AA4B2`:** secondary text, metadata, and supporting copy.

### Network support palette

- **Deep Green `#224C36`:** toggle tracks, selected/low-emphasis green surfaces.
- **Network Blue `#1E3A5F`:** logo outline, map/network geometry, and stable technical structure.
- **Electric Blue `#2563EB`:** optional data/map emphasis; never compete with Signal Green for primary actions.
- **Radio Cyan `#06B6D4`:** optional signal/radio highlight in diagrams and firmware.
- **Lime Signal `#B7F21D`:** rare highlight for high-energy artwork or small signal details. Do not use for body text.
- **White `#FFFFFF`:** reversed text and logo details on dark backgrounds.

### Usage ratios

Aim for roughly **65% graphite/surfaces, 25% text and neutral space, 10% green/blue signal accents**. Green is a signal, not a wallpaper. Blue supports the network story; it should not become a second competing CTA color.

### Accessibility

Use `#E6EAF0` on `#222222` or `#303030` for primary text. Use Signal Green for indicators and large/high-emphasis accents. For normal-size white button text, use accessible Green `#267342` (or a darker green), not bright Signal Green `#36A167`. On light backgrounds use `#2F8F4E`, never `#36A167`, for text-sized links or controls. Never place muted text over the dark canvas when it is the only way to understand an action.

## Typography

**Inter** is the primary family. Use the same family on the web, in promotional graphics, and in firmware where a suitable Inter-like font is unavailable. Firmware fallback order: `Inter → DejaVu Sans → system sans`.

- Display: 700, tight tracking, sentence case.
- Headings: 600, clear and compact.
- Body: 400, generous 1.6 line-height.
- Eyebrows/labels: 700, uppercase, `0.14em` tracking.
- Technical values: JetBrains Mono or a device monospace fallback.

Do not use condensed techno fonts, excessive all-caps, or more than two font families in one composition.

## Layout

- Use a max content width around **1200px** on the web.
- Use a **4px base grid**; common spacing is 8, 16, 24, 36, and 48px.
- Cards use 14px corners; small inset/code surfaces use 10px; actions are pill-shaped.
- Keep borders thin and quiet: white at about 8% opacity on dark surfaces, black at about 8% on light surfaces.
- Use a single restrained shadow: dark mode `0 10px 30px rgba(0,0,0,.45)`; light mode `0 8px 20px rgba(0,0,0,.08)`.
- Prefer one strong primary action per region.

## Elevation & Depth

Depth comes from graphite steps, a 1px border, and a restrained shadow. A green top rule or small green status dot is preferred to a large glow. Gradients are allowed only as quiet atmospheric background texture or in logo artwork; avoid neon gradients behind normal reading content.

## Shapes

The logo combines an Australia silhouette, central antenna, radio waves, and a curved horizon. Preserve the idea of **one central mast distributing signal across a connected landscape**. Supporting graphics may use arcs, node lines, route paths, map contours, and small status dots.

## Components

### Web

- Primary buttons: Signal Green fill, white text, pill shape.
- Secondary buttons: transparent/green-soft fill, primary text, quiet border.
- Cards: Surface background, 1px border, 14px radius, 24px padding.
- Status: green dot plus plain-language label; do not rely on color alone.
- Maps: dark or neutral base with blue structure and green active coverage/signal.
- Code: Surface Soft background, 10px radius, monospace text, safe wrapping.

### Print

Use the dark graphite background when printing on a dark or premium substrate. For ordinary white paper, use white space with Network Blue structure, Signal Green accents, and `#1F2937` body text. Keep small type at least 8pt and preserve strong contrast. Provide a one-color version in Network Blue or black when production constraints require it.

### Firmware / CYD

Use dark mode by default: canvas `#222222`, panel `#303030`, text `#E6EAF0`, muted `#9AA4B2`, active/online `#36A167`, warning/attention `#B7F21D` only for brief highlights. Prefer solid fills over gradients, avoid large shadows, and use 2–4px signal dots or arcs. Make state understandable through icon/label/shape as well as color because displays may be viewed in sunlight or by users with color-vision differences.

Recommended small-screen hierarchy:

1. EastMesh mark or wordmark.
2. Current state / node name.
3. One large primary value.
4. Supporting metadata.
5. Small signal/status indicator.

## Do's and Don'ts

### Do

- Keep the green accent meaningful: active, online, join, connect, view.
- Pair radio-wave or map geometry with simple copy.
- Use the dark theme as the default product signature.
- Keep the logo clear and recognisable at every size.
- Use `eastmesh.au` in lowercase in running text and URLs.

### Don't

- Do not recolour the logo arbitrarily or add competing brand colours.
- Do not stretch, rotate, crop, or place the logo over a busy image without a quiet backing area.
- Do not use green for every heading, border, and paragraph.
- Do not use pure black and pure white as the normal UI palette when graphite and off-white are available.
- Do not rely on color alone for device state, coverage, warnings, or errors.

## Assets and implementation

- Current logo: `assets/logo.png`.
- Simple Australia outline mark: `assets/eastmesh-icon.svg`.
- Web token export: `brand/tokens.css`.
- Machine-readable token export: `brand/tokens.json`.
- Visual/printable reference: `brand/brand-guide.html`.

The website's current CSS variables remain the baseline implementation. New projects should import the token file and use semantic names rather than hard-coding hex values throughout components.
