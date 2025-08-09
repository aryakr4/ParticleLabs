A particle simulation. Needs adjusting.

# Particle Lab — Interactive Particle Simulation

Particle Lab is a lightweight, browser-based particle system that demonstrates emergent motion from simple rules.  
You can adjust parameters, add particles, and watch complex behaviors form in real time — no GPU or frameworks required.

## Features

- **Interactive controls** — Adjust speed, particle count, link distance, and mouse influence.
- **Real-time animation** — Runs at 60 FPS using the Canvas API.
- **Efficient** — Spatial hashing for smooth performance with thousands of particles.
- **Accessible** — Respects "reduced motion" settings and works on both mobile and desktop.
- **Portable** — A single HTML file with no dependencies.

## Live Demo

Open `simulation.html` in any modern browser and start interacting:
- Drag to attract or repel particles.
- Hold `Shift` while dragging to repel.
- Use the sliders in the control panel to tweak parameters.
- Add particles with the **+100** button or reset to defaults.

## How It Works

Particles follow simple behavioral rules:
- **Cohesion** — Move toward nearby particles.
- **Separation** — Avoid getting too close.
- **Alignment** — Match velocity with neighbors.
- **Noise** — Add slight randomness for organic motion.

These rules combine to create smooth, lifelike motion.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git

