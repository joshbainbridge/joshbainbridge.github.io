---
layout: project
title: Physically Based Renderer
order: 1
date: 2015, Jun
---

My masters thesis consisted of implementing the rendering architecture described in [Disney's paper](http://www.fxguide.com/featured/disneys-new-production-renderer-hyperion-yes-disney/) 'Sorted Deferred Shading For Production Path Tracing' and testing the architecture's performance. The primary goal was the development of a system capable of handling production scale data sets, while still being scalable and allowing for artistic iteration. I also took into consideration industry standards for colour and image management. The principles behind it's design are as follows.

- Efficient data access through localisation in time and space
- Object orientation and abstraction for higher level operations
- Data orientation and optimisations for performance critical processes
- Encapsulation only for polymorphism and extendible functionality
- Concurrent model of execution

This project was developed in c++ and is written as an independent library, although a command line tool and opengl framebuffer are also included as an example of progressive rendering. The thesis itself can be accessed [here](@root_path/files/bainbridge_joshua_thesis.pdf) which gives the theoretical background and details on implementation.

Follow [this link](https://github.com/joshbainbridge/msc-project) to the GitHub project.

<p id="media">
<img src="@path/image_one.jpg" alt="@title" width="540px">
<img src="@path/image_two.jpg" alt="@title" width="540px">
<iframe src="https://player.vimeo.com/video/137107761?color=ffffff&title=0&byline=0&portrait=0" width="540" height="303" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</p>