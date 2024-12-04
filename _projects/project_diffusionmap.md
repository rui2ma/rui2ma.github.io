---
layout: page
title: Dimension Reduction Technique
description: Embed higher-dimensional data on representative lower-dimensional manifold.
img: assets/img/project_diffusionmap/cover.png
importance: 4
category: project
related_publications: false
---

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_diffusionmap/image_data.png" title="example image" class="img-fluid rounded z-depth-1"%}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        In this project we sought to find lower dimensional structure presented in higher-dimensional data through various nonlinear dimension reduction techniques. Diffusion map adopts a probabilistic approach to dimension reduction by performing random walk on the high dimensional feature space. I investigated its effectiveness in dimension reduction on simulated data and real image data. The left figure shows diffusion map reducing high dimensional image data to a 1D representation, which can be interpreted as the rotation angle of the images.
    </div>
</div>

<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/project_diffusionmap/poster_final.png" title="example image" class="img-fluid rounded z-depth-1"%}
    Poster for the nonlinear dimension reduction project.
</div>
