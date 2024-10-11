---
layout: page
title: Reinforcement Learning for Flying Insect Robots
description: 
img: assets/img/proj_3/project_background_gif.gif
importance: 4
category: Graduate
--- 


This project focuses on developing a corridor-following behavior for flying insect robots in a non-linear corridor using pure camera input. To facilitate optical flow perception, rich textures were added to the corridor walls. The agent is equipped with two cameras, one pointing left and the other right, to gather visual information for navigation. During the training phase, the robot also utilizes additional sensors to measure deviations from the reference position, which are used to compute rewards. The agent is trained using the Proximal Policy Optimization (PPO) algorithm, a state-of-the-art reinforcement learning technique within the policy gradient method family. This approach enables the agent to learn effective navigation strategies by optimizing its policy based on environmental feedback. The project demonstrates the potential of reinforcement learning in enhancing autonomous navigation for insect-sized flying robots. The code and the report for the project can be found [here](https://github.com/amantiwary10/CSE571-IntelligentControl).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/proj_3/training_video_1.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/proj_3/training_video_2.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<style>
.custom-dimensions {
    width: 100%;
    height: 300px; /* Set your desired height */
    object-fit: cover; /* Ensures the content covers the area */
}
</style>