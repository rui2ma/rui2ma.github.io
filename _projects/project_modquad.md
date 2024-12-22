---
layout: page
title: Multi-rotor Aerial Vehicles Control
description: Deep reinforcement learning based control for multi-rotor aerial vehicles.
img: assets/img/project_modquad/cover.png    
importance: 1
category: project
related_publications: false
---

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        <div class="col">
            <div class="col-sm mt-3 mt-md-0">
                {% include figure.liquid loading="eager" path="assets/img/project_modquad/zoo.png" title="example image" class="img-fluid rounded z-depth-1" %}
            </div>
            <div class="col-sm mt-3 mt-md-0">
                {% include figure.liquid loading="eager" path="assets/img/project_modquad/4x4_hover.gif" title="example image" class="img-fluid rounded z-depth-1" %}
            </div>
        </div>
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        <div class="col-sm mt-3 mt-md-0">
            In this independent study, I applied deep reinforcement learning (deep RL) techniques to develop controllers for <a href="https://www.grasp.upenn.edu/projects/modquad-assembling-structures-in-midair/">ModQuad</a>, a special type of multi-rotor aerial vehicle consisting of modular flying structures. I deployed a model-free Proximal Policy Optimization (PPO) approach to training controllers for a zoo of different ModQuad structures (shown in the left figure). The trained controller can robustly stabilize ModQuad at fixed points from various starting conditions and in the presence of external force disturbances.

            Additionally, leveraging the trained RL controller, I devised a artificial potential field based approach to online path planning, which enabled the ModQuad to follow a series of waypoints without having to pre-compute the entire trajectory offline.
        </div>
    </div>

</div>



<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="420" height="250"
            src="https://www.youtube.com/embed/IoR_4Uabar8?si=y7T8egJcrvZxoYfM" allow="fullscreen;">
        </iframe>
        Deep RL policy controls a ModQuad to hover at a fixed point.
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="420" height="250"
            src="https://www.youtube.com/embed/NzzA0ew_FCI?si=S7x6T0m1yf3uZnz9" allow="fullscreen;">
        </iframe>
        Artificial potential field based waypoints following for a 2x2 ModQuad. Waypoints indicated by blue dots. 
    </div>
</div>

