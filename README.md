# BombSquad Asset Reference

A browser-based reference tool for exploring BombSquad's game assets - textures and 3D meshes - built for modders, mappers, and anyone digging into the game's files.

## Features

### 🎨 Texture Reference
- Browse all in-game textures across 22 categories (characters, bombs, powerups, UI, achievements, medals, fonts, and more)
- Live search/filter by name
- Click any texture name to instantly copy the name to your clipboard
- Hover preview shows the actual image before you commit to using it

### 🧊 Mesh Reference
- Click on any name to to view a full 3D preview of any `.obj` mesh, rendered with Three.js
- Orbit controls - drag to rotate, scroll to zoom, right-click to pan
- Toggleable display modes:
  - Wireframe
  - Flat shading
  - Sharp lighting
  - Real-time shadows
  - Reference grid
- Apply any of the reference textures directly onto a loaded mesh to see how it wraps using the mesh's real UV data - no artificial tiling or distortion
- Upload your own custom PNG to preview how a new/edited texture will look on a real mesh before dropping it into the game
- On-screen labels show which mesh and which texture (or "custom" for uploads) are currently active

## Tech Usage
- Vanilla HTML/CSS/JS
- [Three.js](https://threejs.org/) (r158) for 3D rendering
- No build steps and no dependencies to install

<div align="center">

### 🚀 [**VISIT THE LIVE SITE**](https://vishal332008.github.io/BombSquad-Asset-Reference) 🚀

</div>

---

## Usage

- **Textures page:** From the homepage, head to the Textures section to search or browse by category. Click any texture name to copy the name to your clipboard, and hover over it to preview the actual image.
- **Meshes page:** Head to the Meshes section and pick a mesh to open it in the 3D viewer. From there, use the ⚙️ Settings panel for display options (wireframe, shading, lighting, shadows, grid) and the 🎨 Texture panel to search and preview textures directly on the loaded mesh - or upload your own PNG to test a custom texture.

## Credits

Made by **@vishyyy338** & **@chrosticey**

## Disclaimer

This is an unofficial fan-made reference tool. BombSquad is developed by Eric Froemling. All game assets referenced here belong to their original creators and are used solely for reference/documentation purposes.
