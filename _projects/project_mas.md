---
layout: page
title: Multi-agent Flocking Control
description: Coupled oscillator model for various multi-agent flocking patterns.
img: assets/img/project_mas/cover.png
importance: 2
category: project
related_publications: false
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="480" height="200" src="https://www.youtube.com/embed/V4f_1_r80RY?si=164Ny-Xuc3FksAfc" allow="fullscreen;">
        </iframe>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Flocking is commonly observed in many multi-agent systems (MAS) in nature. The video on the left showcases a spectacular example of flocking in the flight of starlings. The complex system-level behavior cannot be achieved with a central planner. Instead, a distributed decision process must be adopted in such systems. Inspired by this observation, I started a project exploring the flocking behavior of an artificial collective.
    </div>
</div>
Inspired by the [Kuramoto Model](https://en.wikipedia.org/wiki/Kuramoto_model) and the work by [Paley et al.](https://ieeexplore.ieee.org/document/4272331), I extended the coupled oscillator model to 3D space, and derived a distributed control law that enabled agents to coordinate with each other through local decision-making such that various global flocking pattern emerges (as shown by videos below).
<div class="row justify-content-sm-center">
     <div class="col-sm mt-3 mt-md-0">
        <iframe width="400" height="250" src="https://www.youtube.com/embed/-7_aEYh-Vvo?si=jbLNnHsaD5z21gKn" allow="fullscreen;">
        </iframe>
    </div>
     <div class="col-sm mt-3 mt-md-0">
        <iframe width="400" height="250" src="https://www.youtube.com/embed/AiQu9Lm-CiM?si=0zGnRuMlomsHHfGX" allow="fullscreen;">
        </iframe>
    </div>
     <div class="col-sm mt-3 mt-md-0">
        <iframe width="400" height="250" src="https://www.youtube.com/embed/ZhYW2a_w2KQ?si=-pi2tvew0s-k2oAC" allow="fullscreen;">
        </iframe>
    </div>
     <div class="col-sm mt-3 mt-md-0">
        <iframe width="400" height="250" src="https://www.youtube.com/embed/ki-ePEDjRYI?si=A3ZCPN9xcgpWeCk5" allow="fullscreen;">
        </iframe>
    </div>
</div>

<div class="row mt-3"></div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_mas/3d_cube.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_mas/3d_tunnel_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        The proposed controller also allowed the flocking collective to track reference trajectories, which is more suitable for engineering applications.
    </div>
</div>