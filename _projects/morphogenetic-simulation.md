---
layout: project
title: Morphogenetic Simulation
order: 2
date: 2014, Oct
---

This c++ project was my submission for the Animation and Software Engineering module I did while studying at Bournemouth University. It is the simulation of a morphogenetic process, based upon the paper 'Cellular Forms' by Andy Lomas. I also wrote a multi-threaded path tracer (based upon Kajiya's original design) to visualize the cells with an interactive user interface using NGL and the Qt library.

- Cellular simulation
- Physically based renderer
- OpenGL visualiser and Qt interface
- Modular design

The renderer is multi-threaded and uses a task based system to handle work loads between threads. It has a modular design influenced by renders such as PBRT and Mitsuba with extendible interfaces to many of the core features. A standalone version of the renderer featuring a scene description format and command line access can also be found on my github page. 

Follow [this link](https://github.com/joshbainbridge/morphogenetic-sim) to the GitHub project.

<p id="media">
<img src="@path/output_two.jpg" alt="@title" width="540px">
<img src="@path/output_one.jpg" alt="@title" width="540px">
<iframe src="https://player.vimeo.com/video/124716574?color=ffffff&title=0&byline=0&portrait=0" width="540" height="227" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<iframe src="https://player.vimeo.com/video/124678271?color=ffffff&title=0&byline=0&portrait=0" width="540" height="304" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</p>