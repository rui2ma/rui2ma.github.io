---
layout: page
title: Multi-robot Coverage Control
description: Multi-robot coverage control in unknown environments.
img: assets/img/research_coverage/cover.png
importance: 1
category: research
related_publications: false
---
<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/research_coverage/coverage.png" title="example image" class="img-fluid rounded z-depth-1"  width="300"%}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        I'm currently working on my master's thesis co-advised by <a href="https://www.cis.upenn.edu/~linhphan/">Dr. Linh Phan</a> and <a href="https://www.grasp.upenn.edu/people/ani-hsieh/">Dr. Ani Hsieh</a>. My thesis work tackles a variant of the multi-robot coverage control problem where agents are tasked to find optimal sensor placements to cover a sparse signal distribution in unknown environments - a scenario typical in search and rescue missions. My approach to this problem involves robot online learning of the signal distribution estimation and providing coverage based on the estimate. Shown on the left is a converged robot placement using parametric functions for signal estimation.
    </div>
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        To improve coverage performance, I deployed a non-parametric mixture of gaussian process (MGP) to estimate signal, and a upper-confidence-bound (UCB) to balance robots exploring unknown environments and covering high signal areas (shown on the right). Currently, I'm working on using informed-path planning and adpative sampling to improve the convergence rate and the optimality of sensor placements.
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        <iframe width="560" height="315"
            src="https://www.youtube.com/embed/8WshPLOnrpM?si=2LfRVM-TSPQA_iOq" allow="fullscreen;">
        </iframe>
    </div>
</div>
