# EastMesh brand guide

The reusable visual identity system for [EastMesh](https://eastmesh.au), an Australian community MeshCore / LoRa network.

## Start here

- **[DESIGN.md](DESIGN.md)** — normative brand and design guidance
- **[brand/brand-guide.html](brand/brand-guide.html)** — printable visual reference
- **[brand/tokens.css](brand/tokens.css)** — copy-paste CSS variables
- **[brand/tokens.json](brand/tokens.json)** — machine-readable design tokens
- **[assets/](assets/)** — current logo and icon assets
- **[print/](print/)** — finished print-ready logo and wordmark masters

## Identity

**Community mesh. Local signal.**

The system is designed for websites, maps, dashboards, documentation, physical promotion, stickers, and embedded displays such as the EastMesh CYD notifier. The default character is technical but calm: graphite surfaces, a living green signal, and cool blue network structure.

## Usage

Use `DESIGN.md` as the source of truth. The HTML guide and token files are implementation aids and should remain aligned with it. Do not treat this public repository as a grant of trademark or asset rights; ask before using EastMesh branding for an unrelated service or product.

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/brand/brand-guide.html>.

## Source

The guide was extracted from the existing EastMesh landing implementation and its current logo assets. The standalone repository intentionally excludes the landing site's application code, blog content, deployment files, and exploratory design concepts.
