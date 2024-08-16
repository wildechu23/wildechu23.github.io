---
layout: project
title: 3D Renderer from scratch
date: June 2022
---

A 3D CPU-based renderer developed from scratch.

The screen is represented internally as a NxN 2D array. Features were implemented in order as follows:
- Edge rasterization
- 3D matrix transformations
- Scanline for triangle rasterization
- Z-buffering
- Phong reflection for lighting
- Parser for scene management
- Animation via tweening, with output to .gif
- .obj file loader with textures
- Flat, Gouraud, and Phong shading

Here are some results:

![Dog](/assets/images/835.png)
![Fox](/assets/images/836.gif)
