# Tactical Command | Interactive 3D Portfolio

**Tactical Command** is an immersive, sci-fi themed interactive portfolio website built with **Three.js**. It gamifies the traditional portfolio experience by placing the user in the cockpit of a spaceship, tasked with defending key information nodes while exploring a 3D sector.

## 🚀 Project Overview

*   **Type:** Web Application / Game / Portfolio
*   **Tech Stack:** HTML5, CSS3, JavaScript (Vanilla), Three.js
*   **Theme:** Cyberpunk / Sci-Fi Tactical Interface
*   **Author:** Eric Djavid

## 🎮 Core Mechanics

### Navigation & Combat
*   **Flight:** Isometric spaceship control using `[W][A][S][D]` for movement and `[SPACE]` for boost.
*   **Combat:** Fire energy projectiles with `[ENTER]` to destroy enemies and asteroids.
*   **Camera:** Smooth follow camera with dynamic lag and warp effects.

### Economy & Building
*   **Resources:** Collect **Carbon** by destroying asteroids or automating production.
*   **Construction:** Enter Build Mode `[B]` to deploy structures.
    *   **Basic Tower:** Defensive turret that automatically targets enemies (Cost: 10 Carbon).
    *   **Carbon Factory:** Hexagonal industrial structure that generates 1 Carbon every 10 seconds (Cost: 10 Carbon).

### Enemies & AI
*   **Standard Interceptors:** Fast, agile ships that swarm bases.
*   **Cargo Ships (Bosses):** Massive, heavily armored vessels that appear from Round 5. They are slow but deal massive damage (5x standard).
*   **Wave System:** Progressive difficulty with increasing enemy counts and types.

## 🌟 Key Features

*   **Interactive Nodes:** Fly close to colored beacons (Bases) to access portfolio content:
    *   **Alpha Base:** About Me & Philosophy.
    *   **Project Hub:** Showcase of startups and apps (Buzzclip, Wellia, etc.).
    *   **Comms Relay:** Contact information and social links.
*   **Immersive UI:**
    *   **HUD:** Real-time resource tracking, score, and coordinates.
    *   **Minimap:** Radar system tracking player, enemies, and bases.
    *   **Mission Briefing:** Typewriter-style text transmission with synchronized audio.
*   **Audio System:**
    *   Background music and spatial sound effects (lasers, explosions).
    *   Robust audio handling with a "Click to Initialize" start screen to comply with browser autoplay policies.

## 🛠️ Technical Implementation Details

*   **Three.js Rendering:** Uses `WebGLRenderer` with an `OrthographicCamera` for the isometric look.
*   **Raycasting:** Implements mouse-to-world raycasting for placing buildings on the grid.
*   **State Management:** Centralized `STATE` object tracks game logic (carbon, round, enemies, buildings).
*   **Performance:** Optimized particle effects (explosions, trails) and object pooling concepts for projectiles.

## 📦 Asset Credits
*   **Music:** "Nicholas Panek" from Pixabay.
*   **Sound Effects:** Custom sci-fi audio assets.
