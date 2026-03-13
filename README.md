# canvas-chemdoodle
# Canvas + ChemDoodle Skeleton

This repository contains a minimal setup for embedding ChemDoodle Web Components
into Canvas LMS via an iframe.

## Setup

1. Clone or upload repository to GitHub.
2. Enable GitHub Pages in repository settings (Branch: main, root folder).
3. Ensure `js/ChemDoodleWeb.js` and `css/ChemDoodleWeb.css` are present.
4. Update `editor.html` to point `fetch()` to your backend grading server.

## Canvas Integration

Embed the editor via iframe:

```html
<iframe 
    src="https://svtruksa.github.io/canvas-chemdoodle/editor.html" 
    width="600" 
    height="500" 
    style="border:1px solid #ccc;">
</iframe>
