---
layout: project
title: Radio CAD Rendering
description: Advanced CAD Project
technologies: [Autodesk Fusion]
image: /assets/images/mechanism-optimization.jpg
---

For a class, we were asled to find the maximum height and weight that could be lifted given a rigid bar, an actuator, two pins that must be pinned to the ground, and one that can be pinned anywhere. The dimensions of the box constraining the whole project are given and written in the picture summarizing the problem. I configured a system where the actuator pushes down on the rigid bar, which acts as a lever to lift a weight on the far end of the rigid bar. My rough sketch is shown below.

![Photo of rough sketch]({{ "/assets/images/mechanism-optimization.jpg" | relative_url }}){: .inline-image-l}

As you can see, everything needed is there to solve for an optimized value of height and weight. Once you can obtain height as a funcion of the position of the pin and weight as a function of the position of the pin, multivariable calculus can be use to find the optimal setup for the position of the pin.
