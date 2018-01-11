---
layout: project
title: Reaction Diffusion Equations
order: 3
date: 2015, Jun
---

This was an OpencCL project that integrated a two part reaction diffusion equation using the gray-scott model. The simulation produces activator-substrate behaviour between two chemical morphogens and a wide variety of effects depending upon simple input parameters. I also visualized the results by creating a framebuffer that used the OpenCL and openGL interop to prevent movement of the data between the device and host.

- GPU based implementation
- Interop between OpenCL and OpenGL
- Diverse range of resulting patterns

The device code uses an implicit euler integration that produced stable and fast results with a convolution mask that evaluates diagonal neighbours. You can access a short paper I wrote on the subject [here](@root_path/files/reaction_diffusion_report.pdf) which also has more details on implantation.

Follow [this link](https://github.com/joshbainbridge/reaction-diffusion) to the GitHub project.

<p id="media">
<iframe src="https://player.vimeo.com/video/131013563?color=ffffff&title=0&byline=0&portrait=0" width="540" height="303" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</p>