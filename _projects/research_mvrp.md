---
layout: page
title: Multi-Vehicle Routing
description: Graph neural network based solution to multi-Vehicle Routing Problem.
img: assets/img/research_mvrp/cover.png
importance: 4
category: research
related_publications: false
---

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/research_mvrp/mvrp.png" title="example image" class="img-fluid rounded z-depth-1"  width="300"%}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        In this collaboration research with <a href="https://alelab.seas.upenn.edu/">Alelab</a>, we seek to use a learning-based approach to <a href="https://en.wikipedia.org/wiki/Vehicle_routing_problem">vehicle routing problem</a>. We proposed a layered graph neural network (GNN) architecture consisting of a perception GNN (pGNN) that predicts individual optimal routes, and a communication GNN (cGNN) that coordinates routes between agents. In this work, I utilized expert solutions produced by Google’s ORTools to train the pGNN with imitation learning.
    </div>
</div>