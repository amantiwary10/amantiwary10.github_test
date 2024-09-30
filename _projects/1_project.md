---
layout: page
title: Reinforcement Learning for Flying Insect Robots
description: 
img: assets/img/proj_1/project_background_gif.gif
importance: 1
category: Graduate School
tag: Reinforcement Learning, Airsim, Unreal Enginer
related_publications: false
---


This project focuses on developing a corridor-following behavior for flying insect robots in a non-linear corridor using pure camera input. To facilitate optical flow perception, rich textures were added to the corridor walls. The agent is equipped with two cameras, one pointing left and the other right, to gather visual information for navigation. During the training phase, the robot also utilizes additional sensors to measure deviations from the reference position, which are used to compute rewards. The agent is trained using the Proximal Policy Optimization (PPO) algorithm, a state-of-the-art reinforcement learning technique within the policy gradient method family. This approach enables the agent to learn effective navigation strategies by optimizing its policy based on environmental feedback. The project demonstrates the potential of reinforcement learning in enhancing autonomous navigation for insect-sized flying robots. The code and the report for the project can be found [here](https://github.com/amantiwary10/CSE571-IntelligentControl).