# 5_Symbols — Core Source Code

> The implementation. Where the formula becomes real.

---

## 📁 Contents

This folder holds the actual implementation files: HTML, CSS, JavaScript, and any supporting scripts for the studio project website.

Key files and integrations:

| File | Purpose |
|------|---------|
| `../index.html` | Main entry point — shared navigation menu |
| `../markdown_renderer.html` | Render any `.md` file in the browser |
| `../3_Simulation/carousel.html` | Image carousel for room-layout mockups |
| PrismJS | Syntax highlighting for code blocks in rendered markdown |

---

## 🔧 PrismJS Integration

[PrismJS](https://prismjs.com/) is used to provide syntax highlighting in the markdown renderer.

It is loaded via CDN in `markdown_renderer.html`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/prismjs@1/themes/prism-tomorrow.min.css">
<script src="https://cdn.jsdelivr.net/npm/prismjs@1/prism.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/prismjs@1/plugins/autoloader/prism-autoloader.min.js"></script>
```

---

## 🏗️ Architecture Notes

- Pure static HTML/CSS/JS — no build step required
- GitHub Pages serves the `main` branch root directly
- Marked.js converts Markdown → HTML client-side
- PrismJS highlights code blocks after Marked.js renders them
