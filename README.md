# 3D Realistic Earth

A realistic, interactive 3D Earth rendered in the browser with [Three.js](https://threejs.org). Day/night lighting, atmospheric glow, cloud layer, star field, and orbit controls — all in a single self-contained HTML file with zero build step.

## Features

- **Realistic 3D Earth** — textured sphere with day map, night-lights map, specular highlights, and bump shading
- **Atmosphere & clouds** — additive glow shader for the atmospheric rim plus a slowly rotating cloud layer
- **Interactive controls** — toggle auto-rotation, toggle night lights, reset the camera view
- **OrbitControls** — drag to rotate, scroll to zoom, right-drag to pan
- **Starfield background** — procedural stars generated in-scene
- **Zero build** — single HTML file, open it or serve it statically

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- Three.js r134 (via CDN) + OrbitControls
- Textures loaded from Three.js example assets (`//unpkg.com/three-globe/example/img/`)

## Quick Start

No dependencies, no build.

```bash
git clone https://github.com/girishlade111/3D-Realistic-Earth-.git
cd 3D-Realistic-Earth-
# option 1: just open index.html in a browser
# option 2: serve statically
npx serve .
```

Internet access is required so the browser can fetch Three.js and the earth textures from CDN.

## Project Structure

```
3D-Realistic-Earth-/
├── index.html            # the entire app (markup, styles, Three.js scene)
└── README.md
```

(`3D Realistic Earth 🌍.html` is kept as the original source file.)

## Deploy Notes

Static site — served via GitHub Pages at `https://girishlade111.github.io/3D-Realistic-Earth-/`.

---

Built by Girish Lade — https://ladestack.in
