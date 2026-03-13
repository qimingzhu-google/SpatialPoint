# SpatialPoint: Spatial-aware Point Prediction for Embodied Localization

[Project Page](https://qimingzhu-google.github.io/SpatialPoint/) | [Paper](#) | [arXiv](#) | [Code](#) | [Dataset](#)

![Teaser](assets/figure1.png)

Embodied localization as executable 3D target prediction. SpatialPoint is a depth-aware vision-language framework for predicting camera-frame 3D target points, unifying touchable points and air points for embodied agents.

## Abstract

Embodied intelligence fundamentally requires the capability to determine *where* to act in 3D space. We formalize this requirement as **embodied localization**—the problem of predicting executable 3D points conditioned on visual observations and language instructions. We instantiate embodied localization with two complementary target types: *touchable points*, which are surface-grounded 3D points enabling direct physical interaction, and *air points*, which are free-space 3D points specifying placement and navigation goals, directional constraints, or geometric relations.

Embodied localization is inherently a problem of embodied 3D spatial reasoning—yet most existing vision-language systems rely predominantly on RGB inputs, requiring implicit geometric reconstruction that limits cross-scene generalization, despite the widespread adoption of RGB-D sensors in robotics.

To address this gap, we propose **SpatialPoint**, a spatial-aware vision-language framework with a careful design that integrates structured depth into a vision-language model (VLM) and generates camera-frame 3D coordinates. We construct a 2.6M-sample RGB-D dataset covering both touchable-point and air-point QA pairs for training and evaluation. Extensive experiments demonstrate that incorporating depth into VLMs significantly improves embodied localization performance.

We further validate SpatialPoint through real-robot deployment across three representative tasks: language-guided robotic arm grasping at specified locations, object placement to target destinations, and mobile robot navigation to goal positions.

## Code and Data

The code and dataset are being prepared and will be released here soon.
