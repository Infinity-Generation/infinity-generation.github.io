---
title: "What is Procedural Generation?"
date: 2024-04-19T12:27:48-07:00
description: "In this series, we explore everything about procedural generation."
authors: ["nolankramer"]
tags:
  - new
categories:
  - new
series: ["The Procedural Series"]
series_order: 1
draft: true
weight: 10
featuredImage: ""
---
In this series, we explore everything about procedural generation. We’ll explore the basics, advanced, and state-of-the-art techniques, and discover how procedural generation is currently used in both content creation, and runtime interactive content.

## What is Procedural Generation?

Procedural generation (pc-gen or proc-gen for short) is the science, art, and technique of using _procedures_ (otherwise known as _algorithms_) to create data, typically through a combination of manually created content, computer-generated randomness, models and algorithms.[^1]

Procedural generation typically relies on deterministic 

Procedural generation's claim to fame mostly comes from the game industry, where games like [Dwarf Fortress](https://www.bay12games.com/dwarves/), [Minecraft](https://www.minecraft.net/en-us) or [No Man's Sky](https://www.nomanssky.com/) have heavily relied on the art to produce the entire visible and interactible world for the player to explore.

However, procedural generation plays important roles in everyday life that typically goes unnotice by most individuals and sometimes even the implementors of the proc-gen systems themselves!

Some less-known, but still widely used use-cases are:

- **Weather Forecasting**: Numerical weather prediction models like the Global Forecast System (GFS) developed by the National Centers for Environmental Prediction (NCEP) and the European Centre for Medium-Range Weather Forecasts (ECMWF) Integrated Forecast System (IFS) use procedural generation techniques to simulate atmospheric conditions and forecast weather.
- **Computer-Aided Design (CAD)**: Popular CAD software like Autodesk AutoCAD, SolidWorks, and CATIA heavily utilize procedural modeling techniques for creating and modifying 3D models.[^2]
- **Facial Animation and Lip-Syncing**: Companies like Nvidia, Apple, and Microsoft have developed technologies like Nvidia FaceWorks, ARKit, and Microsoft Lip Sync that use procedural generation for facial animation and lip-syncing in various applications.[^3]
- **Procedural Texture Generation**: Game engines like Unreal Engine and Unity, as well as graphics software like Adobe Substance 3D, have tools and plugins for generating procedural textures. Research papers like "Portable Cloud Maps for Real-Time Procedural Volumetric Rendering" by Bhandari et al. (2021) discuss procedural texture generation techniques.
- **Data Visualization and Infographics**: Popular data visualization tools like Tableau, D3.js, and Infogram utilize procedural generation algorithms to create visualizations. Research in this area includes papers like "Procedural Visualization of Dimensionally-Heterogeneous Data" by Guo et al. (2022).
- **[Diffusion Models](https://en.wikipedia.org/wiki/Diffusion_model)**: Proc-gen is used to generate the seed noise for the denoising model.
- Many roguelike games use procedural generation to randomly generate rooms for the player to explore.
- Erosion simulation: Proc-gen is used to create
- **[Scenery generators](https://en.wikipedia.org/wiki/Scenery_generator)**: Used widely across the games and movies industries to quickly create scenery without much manual effort.

## Humble beginnings

TODO: History

## 

[^1]: <https://en.wikipedia.org/wiki/Procedural_generation>
[^2]: [Example: "Procedural modeling of Architecture" by Wonka et al. (2003)](https://dl.acm.org/doi/abs/10.1145/1185657.1185713)
[^3]: [Example: "Exploring Phonetic Context-Aware Lip-Sync For Talking Face Generation" by Park et al. (2023)](https://arxiv.org/abs/2305.19556)
