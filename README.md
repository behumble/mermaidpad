# MermaidPad

A minimalist, single-file web editor for creating and previewing [Mermaid](https://mermaid.js.org/) diagrams in real time.

## Features

- **Live Preview** — Diagrams render instantly as you type (300ms debounce)
- **Zoom & Pan** — Scroll to zoom, drag to pan, with fit-to-view button
- **Resizable Panes** — Adjustable split between editor and preview
- **Dark / Light Theme** — Catppuccin Mocha dark theme and a clean light theme, with system preference detection and localStorage persistence
- **Zero Setup** — No build tools, no dependencies to install. Just open the HTML file.

## Getting Started

```bash
# Clone the repository
git clone https://github.com/behumble/mermaidpad.git

# Open in your browser
open mermaidpad/index.html
```

That's it. No `npm install`, no build step.

## Usage

1. Write Mermaid diagram syntax in the left editor pane.
2. See the rendered diagram update live in the right preview pane.
3. Use the zoom controls (`+` / `-` / `Fit`) or scroll wheel to adjust the view.
4. Drag the diagram to pan around.
5. Toggle between dark and light themes with the theme button in the toolbar.

## Tech Stack

- **Mermaid.js v11** — Loaded from CDN
- **Vanilla HTML / CSS / JavaScript** — No frameworks, no bundler
- Single `index.html` file (~12 KB)

## Browser Support

Any modern browser with ES module support (Chrome, Firefox, Safari, Edge).

## License

MIT
