# Kanto Academy — JLPT Pokédex RPG

A static HTML/CSS/JavaScript study app with a walkable pixel-art world. No build step or backend required.

## Run locally
Open `index.html` in a browser. For the most reliable asset loading, serve the folder with a local static server (for example, VS Code Live Server).

## Publish on GitHub Pages
Upload `index.html` and the entire `assets/` folder to the root of your repository. Keep the folder names unchanged. Enable GitHub Pages in repository Settings → Pages.

## Controls
- Move: Arrow keys or WASD
- Enter a nearby study center: Enter / on-screen ENTER / STUDY button
- Mobile: use the directional pad
- Return from study mode: BACK TO MAP

## Assets
- `assets/kanto-world-map.png`: custom pixel-art world map
- `assets/trainer-sprites.png`: original 4-direction trainer sprite sheet
- `assets/pixel-landscape.png`: matching background fallback
- `assets/capture-orb.svg`: Pokédex-style decorative orb

Progress/unlocks are stored in browser localStorage. Because this is a static site, progress is specific to that browser/device.
