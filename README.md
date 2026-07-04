# ⛏️ MiniCraft — 3D Voxel World

A browser-based Minecraft-inspired voxel game built with Three.js.

**Play online:** `https://<your-username>.github.io/minecraft-game/`

## Features

- 🌍 Procedurally generated terrain with hills, caves, and trees
- 🧊 8 block types: Grass, Dirt, Stone, Oak Wood, Leaves, Sand, Planks, Cobblestone
- 🎮 First-person controls (WASD + mouse)
- ⛏️ Break blocks (left click) and place blocks (right click)
- 🎯 Block highlighting and hotbar selection
- 🌲 Randomly generated trees
- ☀️ Dynamic lighting with shadows
- 📊 FPS counter and block stats

## Controls

| Key | Action |
|-----|--------|
| W A S D | Move around |
| Space | Jump |
| Shift | Sneak (slow movement) |
| Left Click | Break block |
| Right Click | Place block |
| 1–8 | Select block type |
| Scroll Wheel | Cycle blocks |
| Esc | Pause / Release cursor |

## How to Play

1. Click **Play** to lock the cursor
2. Use WASD to explore the world
3. Left-click blocks to break them
4. Right-click to place the selected block
5. Use number keys or scroll to switch blocks

## Tech

- [Three.js](https://threejs.org/) — 3D rendering engine
- Canvas-generated pixel textures
- Voxel ray marching (DDA algorithm) for block interaction
- PointerLockControls for FPS camera
