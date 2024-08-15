---
layout: project
title: Terrain Generation
---

A prodedural terrain generator written in Typescript using WebGPU, as a demonstration of the Marching Cubes algorithm.

The world is divided into chunks, which are only rendered when in distance. For each chunk, a density texture is created by sampling 3d noise textures. Then the mesh is generated via the Marching Cubes Algorithm and rendered.

[Github](https://github.com/wildechu23/TerrainGen)