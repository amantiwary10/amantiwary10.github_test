---
layout: page
title: Scene Reconstruction
description: Trajectory Optimization for 3D scene reconstrcution
img: assets/img/proj_4/model_based_traj_opt_background.gif
importance: 1
category: Graduate
---

This is my master’s thesis project. The primary objective is to develop a dynamically feasible trajectory for UAVs to perform continuous image acquisition during flight. The algorithm starts with a rough 3D scene proxy, serving as an initial model of the environment. Using this proxy, it computes both the UAV’s trajectory and the corresponding sensor poses necessary for optimal image capture.

The computed trajectory guarantees comprehensive scene coverage while respecting real-world flight constraints, such as velocity and acceleration limits, ensuring dynamic feasibility. The captured images are then processed to reconstruct a detailed, high-quality 3D model of the scene, which has applications in various domains, including inspection, mapping, and virtual reconstruction.

<div class="row mt-3">
    <div class="col mt-3 mt-md-0">
        {% include video.liquid path="assets/video/proj_4/model_based_traj_opt.mp4" class="img-fluid rounded z-depth-1 custom-dimensions" controls=true autoplay=true %}
    </div>
</div>

<style>
.custom-dimensions {
    width: 100%;
    height: 300px; /* Set your desired height */
    object-fit: cover; /* Ensures the content covers the area */
}
</style>