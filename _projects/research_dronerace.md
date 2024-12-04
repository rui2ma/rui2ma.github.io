---
layout: page
title: Agile Quadcopter Flight
description: Deep reinforcement learning for quadcopter racing.
img: assets/img/research_dronerace/cover.png
importance: 2
category: research
related_publications: false
---

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/research_dronerace/v_shape.gif" title="example image" class="img-fluid rounded z-depth-1"  width="300"%}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        Deep reinforcement learning (deep RL) has shown tremendous success in its application to robotic tasks. In this research, I set out to investigate its application in agile quadcopter flight in the setting of drone racing. Additionally, I seek to explore training a deep RL online path planner that enable the quadcopter to fly through unseen race tracks.
    </div>
</div>


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="420" height="250"
            src="https://www.youtube.com/embed/-YMMlcEh4yU?si=w7lCLXG7pK4M9GLw" allow="fullscreen;">
        </iframe>
        Agile quadcopter flight in the square racetrack.
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="420" height="250"
            src="https://www.youtube.com/embed/WTEI17939gU?si=mYOVQGfcvaRXG60r" allow="fullscreen;">
        </iframe>
        Agile quadcopter flight in the S racetrack.
    </div>
</div>


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        Inspired by the curriculum training in <a href="https://arxiv.org/abs/2109.11978">Rudin et al.</a>, I aimed to develop a deep RL model for online quadcopter path planning by training it to incrementally fly through more and more gates. As a first step, I trained the quadcopter to fly through two consecutive gates in different placements (shown in the video on the right). 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="420" height="250"
            src="https://www.youtube.com/embed/sbw99Xk9K5I?si=XoI7s-yPVgN3fSkH" allow="fullscreen" >
        </iframe>
    </div>
    
</div>
