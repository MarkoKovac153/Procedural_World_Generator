# Procedural_World_Generator

This project is an example of a procedurally generated 3D world which uses threading and LOD's to procedurally generate terrain as you (the character) move around the map.

## Table of Contents

- [Overview](#overview)
- [Movement Controls](#MovementControls)
- [Usage](#Usage)

## Overview

This project is a 3D procedural world generator:

- **Procedural Generation**: Generates endless and unique terrains.
- **Chunk-based Generation**: Efficiently creates terrain with smooth transitions.
- **Threaded Terrain Generation**: Utilizes threading for smoother performance.
- **Level of Detail (LOD) Rendering**: Optimizes rendering based on viewer proximity.
- **Dynamic Elements**: Randomly adds rocks, trees, birds, and sheep for realism.
- **Random Seed and Noise Maps**:
  - **Random Seed**: The generation process is initiated with a random seed, which serves as the starting point for creating the terrain. This ensures that each generated world is distinct and unpredictable.
  - **Noise Maps**: Noise maps are employed to introduce organic variations to the terrain. By applying noise functions such as Perlin or Simplex noise, the generator creates natural-looking features like hills, valleys, and ridges. These noise maps serve as the foundation for determining the elevation and topology of the landscape, adding complexity and realism to the generated terrain.

# Movement Controls

This document outlines the basic movement controls for the project.

| Action   | Key(s)              |
|----------|---------------------|
| Forward  | W                   |
| Backward | S                   |
| Left     | A                   |
| Right    | D                   |
| Jump     | Spacebar            |
| Sprint   | Hold Shift + (W/A/S/D) |

# Usage
The project is already built so feel free to jsut install download the repository and run the my project.exe file.
