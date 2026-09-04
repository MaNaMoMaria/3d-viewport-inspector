# 3d-viewport-inspector
# 3D Viewport & BIM Component Inspector

An interactive, code-first 3D WebGL prototype designed to demonstrate real-time spatial component inspection, dynamic architectural cutaways, and lighting control within a modern browser viewport.

Built using **Three.js**, **Tailwind CSS**, and **Lucide Icons**, this project showcases how rapid design intent can be translated directly into functional interactive prototypes using AI-assisted development workflows.

---

## 🚀 Key Features

* **Interactive 3D Viewport:** Real-time orbit navigation, zoom, and panning powered by Three.js `OrbitControls`.
* **Raycasting & Inspection:** Click on any 3D BIM structural element (slabs, columns, curtain walls) to highlight it and reveal technical parametric data in the **BIM Inspector** drawer.
* **Dynamic Cutaway Action:** Hide selected structural elements on the fly (or press `H`) to inspect concealed internal components.
* **Viewport Shading & Lighting Modes:** Toggle environment scene lighting, inspect wireframe wire-mesh architecture, or switch to X-Ray structural opacity mode.
* **Keyboard Shortcuts:**
  * `H` - Hide currently selected element (Cutaway).
  * `R` - Reset camera position and restore hidden objects.
  * `Esc` - Deselect current object and close inspector panel.

---

## 🛠️ Tech Stack & Architecture

* **3D Engine:** [Three.js](https://threejs.org/) (WebGL / Raycasting / Physical Materials)
* **Styling & Layout:** [Tailwind CSS](https://tailwindcss.com/) (Glassmorphism UI overlay)
* **Icons:** [Lucide Icons](https://lucide.dev/)
* **Methodology:** Code-First Prototyping & AI-Assisted Front-End Integration

---

## 📂 Project Structure
