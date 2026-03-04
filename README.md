# Gästhus 3D

A first-person 3D viewer for exploring an architectural model of a guest house (gästhus). Built with Three.js, it loads STL files and renders them in a walkable environment with realistic lighting and materials.

## Features

- **First-person controls** — WASD/arrow keys to move, mouse to look, space to jump, shift to sprint
- **STL model loading** — Loads and assembles multiple STL parts (foundation, walls, roof) with axis conversion (Z-up to Y-up)
- **PBR materials** — Procedurally generated bump and roughness maps for concrete, wood, and plaster surfaces
- **Collision detection** — Raycasting-based wall and ground collision at multiple body heights
- **Step-up system** — Automatically steps over low obstacles like door thresholds and foundation edges
- **Interior lighting** — Point light inside the house with shadow casting
- **Sky and environment** — Gradient sky shader, fog, and ground grid



## Controls

| Key | Action |
|-----|--------|
| W / Arrow Up | Move forward |
| S / Arrow Down | Move backward |
| A / Arrow Left | Move left |
| D / Arrow Right | Move right |
| Space | Jump |
| Shift | Sprint |
| Mouse | Look around |
| ESC | Release cursor |