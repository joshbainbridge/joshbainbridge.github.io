---
layout: project
title: Layered RSL Shader Model
order: 4
date: 2015, Jun
---

This was an rsl shader project I did while at Bournemouth University. I used the python api for renderman to define the scene, as this allowed me to load the geometry from an external file. The scene was then configured to render using the progressive sampler that can be enabled in photorealistic renderman 18. The first two shaders I created were to handle dielectric and diffuse surfaces. These were both designed in accordance to modern rsl and the pipeline methods outlined in pixar's documentation, producing physically based results.

- Layered shader model
- Physically based
- Render any .obj file
- Russian roulette sampling

I then wrote a layered shader to allow the combination of two input shaders. This could be either a dielectric, diffuse or even another layered shader allowing for a stacked design. Each layer used a russian roulette approach to sampling its inputs so that branching was reduced and iteration cycles were faster. A short paper I wrote can be accessed [here](/assets/data/rendering_report.pdf) that outlines the theory and implementation in more detail.

You can download the project, including rsl shaders and python code [here](/assets/data/rendering_project.zip).

<p id="media">
<img src="/assets/img/rendering_project_master.jpg" alt="@title" width="540px">
<img src="/assets/img/rendering_project_second.jpg" alt="@title" width="540px">
</p>