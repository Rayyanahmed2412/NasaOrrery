# NasaOrrery

An interactive 3D solar system orrery built with Three.js, featuring realistic planetary textures, orbital motion, and user-controlled navigation.

---

## Features

- **Accurate planetary visuals** – High-resolution textures for the Sun, planets, Moon, and Saturn’s rings.
- **Real-time orbital motion** – Each celestial body moves in its orbit with sizes and speeds approximated proportionally.
- **User interaction** – Pan, zoom, and rotate the view to explore the solar system freely.
- **Optimized for performance** – Lightweight and smooth rendering via efficient Three.js code.

---

## Demo

To run the orrery locally:

1. Clone this repo:

   ```bash
   git clone https://github.com/Rayyanahmed2412/NasaOrrery.git
   cd NasaOrrery
   ```

2. Install dependencies (if needed, e.g. with `npm`):

   ```bash
   npm install
   ```

3. Serve the files using a local HTTP server (e.g., `live-server`, `http-server`, VSCode Live Server, or Python’s `http.server`):
   ```bash
   # Example using python 3
   python -m http.server 8000
   ```
4. Open your browser and navigate to `http://localhost:8000` to explore the orrery!

---

## Project Structure

```
├── index.html           // Main entry point for the orrery
├── Orrery.js            // Three.js scene setup, animation, and controls
├── style.css            // Basic styling (if any)
├── package.json         // Project metadata and dependencies
├── package-lock.json    // Exact dependency versions
├── *.jpg / .png / .svg  // Textures and images for celestial bodies
└── .gitignore
```

---

## Technologies Used

- **[Three.js](https://threejs.org/)** – JavaScript 3D library powering the scene.
- **JavaScript/HTML/CSS** – Core frontend technologies.
