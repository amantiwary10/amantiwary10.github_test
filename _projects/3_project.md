---
layout: page
title: Gaussian Process Regression for Li-Ion battery modeling
description: 
img: assets/img/proj_3/battery_model_project_background.png
importance: 4
category: Graduate
---

This project focuses on employing Gaussian Process Regression (GPR) to model the behavior of lithium-ion (Li-ion) batteries, specifically predicting key parameters like resistance and capacitance. GPR is used to develop a probabilistic framework for battery behavior modeling by leveraging discharge pulse data. Radial Basis Function (RBF) and Matern kernels are implemented and compared in terms of mean squared error. Results show that GPR, when paired with the appropriate kernel, effectively models the battery's discharge behavior, offering insights into areas of high variance and uncertainty. The study concludes by validating GPR’s performance against alternative machine learning methods like Genetic Algorithms and Sparse Identification of Nonlinear Dynamics (SINDy), emphasizing its utility in predicting battery performance and system parameters. The code and project report can be found [here](https://github.com/amantiwary10/ME599-Data-Driven-Dynamics/tree/main).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_3/20d-conditional-main.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>