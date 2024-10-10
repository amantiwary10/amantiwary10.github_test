---
layout: page
title: PTR
description: Penalized Trust Region method for minimum time of flight
img: 
importance: 2
category: Graduate
---

This is a python implementation of Chapter  [Convexification and Real-Time On-Board Optimization for Agile Quad-Rotor Maneuvering and Obstacle Avoidance](https://ieeexplore.ieee.org/abstract/document/8206363) by Miki Szmuk. The animation on the left is obstacle avoidance using 3dof quadrotor model. The animation on the right is using 6dof quadrotor model with line-of-sight constraint.

<div class="row mt-3">
    <div class="col mt-3 mt-md-0">
        {% include video.liquid path="assets/video/proj_5/3dof-ptr.mp4" class="img-fluid rounded z-depth-1 custom-dimensions" controls=true autoplay=true %}
    </div>
    <div class="col mt-3 mt-md-0">
        {% include video.liquid path="assets/video/proj_5/6dof-ptr-los.mp4" class="img-fluid rounded z-depth-1 custom-dimensions" controls=true autoplay=true %}
    </div>
</div>

<style>
.custom-dimensions {
    width: 100%;
    height: 300px; /* Set your desired height */
    object-fit: cover; /* Ensures the content covers the area */
}
</style>