# EastMesh agent guidance

This repository is the source of truth for EastMesh visual identity. Use it whenever creating or reviewing EastMesh web pages, dashboards, maps, documentation, promotional material, or embedded-display interfaces.

## Source of truth

1. Read `DESIGN.md` before designing or changing a branded surface.
2. Use `brand/tokens.css` for CSS custom properties and `brand/tokens.json` for tooling.
3. Reuse assets from `assets/` and `print/`; do not redraw or recolour the logo without approval.
4. Use `design-system-preview.html` as a rendered reference for the intended visual posture, not as a replacement for the normative tokens and guidance.

## EastMesh design posture

EastMesh is **technical but calm**: community-run, useful, local, and alive. The core phrase is **Community mesh. Local signal.**

- Default canvas: Graphite / Ink `#222222`.
- Raised surfaces: `#303030` and `#343434`.
- Primary active/action signal: Signal Green `#36A167` on dark surfaces; use accessible `#267342` for normal-size white button text and light surfaces.
- Network structure: Network Blue `#1E3A5F`; Electric Blue and Radio Cyan are supporting accents, not competing primary actions.
- Lime `#B7F21D` is a rare highlight only; never use it for body text.
- Typography: Inter for interface and prose; JetBrains Mono for technical values.
- Shapes: 14px cards, 10px inset/code surfaces, pill-shaped actions.
- Depth: graphite steps, quiet 1px borders, and restrained shadows.
- Geometry: use nodes, routes, arcs, map contours, and status dots when they communicate network relationships.

## Composition rules

Choose the surface archetype before writing markup or CSS:

- **Monitor:** dashboards and live network state; prioritise glanceable density.
- **Operate:** consoles and admin tools; prioritise action and selection state.
- **Explore:** maps and searchable collections; prioritise filters and results.
- **Command / Inspect:** node detail and technical inspection; prioritise focus and speed.
- **Decide / Learn:** landing pages and documentation; prioritise one idea per section.
- **Configure:** setup and settings; prioritise progressive disclosure and validation.

Do not default every page to a centred hero plus three equal cards. Do not use generic Claude/SaaS styling, cyberpunk type, excessive gradients, glassmorphism, arbitrary icon grids, or green as wallpaper. Green should communicate action, activity, or connection.

## Accessibility and content

- Never communicate device state, coverage, warning, or error through colour alone.
- Maintain readable contrast using the documented light and dark combinations.
- Preserve keyboard focus states and mobile hit targets of at least 44px.
- Use sentence case for headings; reserve tracked uppercase text for short labels.
- Do not invent metrics, claims, testimonials, or filler copy. Mark non-final copy as draft.

## Implementation workflow

1. Inspect the relevant existing page, component, and token files before inventing new patterns.
2. State the primary surface archetype and the intended hierarchy in the change description.
3. Implement with semantic HTML, CSS variables, responsive behavior, and reduced-motion support where applicable.
4. Run the page locally and verify desktop and mobile rendering, key interactions, and console errors.
5. Compare the result with `DESIGN.md` and `design-system-preview.html`; fix drift before requesting review.
6. Keep this repository's guide and tokens aligned when the identity itself changes. Do not silently change brand tokens for a one-off page.

## Verification checklist

Before declaring a branded artifact complete, confirm:

- `DESIGN.md` and the token files were consulted.
- The chosen composition matches the surface archetype.
- The EastMesh palette, typography, shapes, and logo usage are consistent.
- Dark and responsive states were checked where supported.
- Important state is expressed with text, shape, or icon as well as colour.
- No generic AI-design patterns or invented content were introduced.
- The final diff contains only intended files.
