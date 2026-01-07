---
title: "Isometric"
date: 2023-11-23T00:00:00-08:00
draft: false
category: "personal"
image: "/images/Isometric/Title.png"
projectYear: "2022"
role: "Programmer and Designer"
tags: ["tool", "isometric", "personal"]
description: "An isometric map editor in Unity."
---

A custom tool built to handle isometric sorting.

<style>
.project-gallery img {
  width: 100%;
  max-width: 500px;
  height: auto;
  border-radius: 8px;
  margin: 1rem 0;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.project-gallery h3 {
  margin-top: 2rem;
  margin-bottom: 0.5rem;
}
</style>

<div class="project-gallery">

![Isometric Title](/images/Isometric/Title.png)

### Sorting Comparison
<div style="display: flex; gap: 1rem; flex-wrap: wrap;">
  <div style="flex: 1; min-width: 250px;">
    <p style="text-align: center; color: var(--secondary); margin-bottom: 0.5rem;">Before Moving</p>
    <img src="/images/Isometric/before.png" alt="Before Moving" style="max-width: 100%; width: 100%; height: auto; border-radius: 8px; margin: 0; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);" />
  </div>
  <div style="flex: 1; min-width: 250px;">
    <p style="text-align: center; color: var(--secondary); margin-bottom: 0.5rem;">After Moving</p>
    <img src="/images/Isometric/after.png" alt="After Moving" style="max-width: 100%; width: 100%; height: auto; border-radius: 8px; margin: 0; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);" />
  </div>
</div>

### Tile Selection
Precise mouse-to-grid selection logic.
![Selection Tool](/images/Isometric/selection.png)

</div>

## Features

- Placing and snapping objects
- Custom isometric tile angle, ratio and height

## Technical Details

Built with C# and Unity, implements topological sorting to handle overlapping sprites.

**Role: Programmer**
