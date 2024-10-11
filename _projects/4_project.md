---
layout: page
title: Camera Network Optimization
description: 
img: assets/img/proj_1/network_opt.gifs
importance: 2
category: Graduate
---

This project focuses on optimizing imaging positions for applications such as object inspection and 3D scene reconstruction, where multiple sensor readings from various viewpoints are required to capture a complete and accurate model of an object's surface. By leveraging an integer programming framework, the best viewpoints are identified by factoring in visibility and occlusions to ensure comprehensive coverage and efficient data acquisition.

<div class="row mt-3">
    <div class="col mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_1/Viewpoint_Candidate.png" title="example image" class="img-fluid rounded z-depth-1 custom-dimensions" %}
    </div>
    <div class="col mt-3 mt-md-0">
        {% include video.liquid path="assets/video/proj_1/cam_net_opt.mp4" class="img-fluid rounded z-depth-1 custom-dimensions" controls=true autoplay=true %}
    </div>
</div>

<style>
.custom-dimensions {
    width: 100%;
    height: 300px; /* Set your desired height */
    object-fit: cover; /* Ensures the content covers the area */
}
</style>