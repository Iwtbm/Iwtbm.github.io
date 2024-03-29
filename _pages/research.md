---
layout: single
permalink: /research/
title: "Research Summary"
author_profile: true
# redirect_from:
---

{% include base_path %}

## Exoskeleton Glove for Patients with Brachial Plexus Injuries
The research focuses on the development of an exoskeleton glove system for people who suffer from brachial plexus injuries, aiming to assist their lost grasping functionality. The robotic system consists of a portable glove system and an embedded controller. The glove system consists of Linear Series Elastic Actuators, Rotary Series Elastic Actuators, and optimized finger linkages to provide imitated human motion to each finger and a coupled hand motion. The design principles and optimization strategies were investigated to balance functionality, portability, and stability. The model-based force control strategy compensated with a backlash model, and the model-free force control strategy are proposed and compared. Results show that our proposed model-free control method achieves the goal of accurate force control. Customized voice activation is also integrated. The proposed exoskeleton glove system has passed the clinical experiments with voluntary patients.  

<iframe width="560" height="315" src="https://www.youtube.com/embed/5inX3800Thc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>  

<br/>
a vision-based HMI system to estimate the initial grasp force using a combination of object detection and material recognition with deep convolutional neural networks to solve the force planning issues. 
<p align="center">
<img src='/images/HMI.jpg' width="80%">
</p>

## Development of a Novel Low-profile Robotic Exoskeleton Glove

The key idea of this new glove lies in its new finger mechanism that takes advantage of the rigid coupling hybrid mechanism concept. This mechanism concept couples the motions of the adjacent human finger links using rigid coupling mechanisms so that the overall mechanism motion (e.g., bending, extension, etc.) could be achieved using fewer actuators. The finger mechanism utilizes the single degree of freedom case of the RCHM that uses a rack-and-pinion mechanism as the rigid coupling mechanism. This special arrangement enables to design each finger mechanism of the glove as thin as possible while maintaining mechanical robustness simultaneously. 

<p align="center">
<img src='/images/new_glove.jpg' width="70%">
</p>

A simulation environment was established to implement diverse deep reinforcement learning algorithms, facilitating intelligent control of various grasp types while ensuring appropriate force management.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_o2xryaBQUY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br/>

<!-- <p align="center">
<img src='/images/cylinder_grasp.gif' width="70%">
</p> -->

<p float="left">
  <img src="/images/cylinder.gif" width="350" />
  <img src="/images/sphere.gif" width="350" /> 
  <img src="/images/tip.gif" width="350" /> 
  <img src="/images/tripod.gif" width="350" /> 
  <img src="/images/literal.gif" width="350" /> 
</p>

## Design of the first generation tactile sensor fingertips
•	Developed a prototype of exoskeleton fingertips based on tactile sensors, built the Unified Robotics Description Format (URDF) configuration for the indenter machine, and path planning in ROS, contributing to developing a precise testing platform.

•	Utilized MATLAB to collect and preprocess data, enabling accurate analysis and interpretation of results, and contributed to training the finger by utilizing machine learning techniques.

<p align="center">
<img src='/images/fingertips.jpg' width="70%">
</p>

## SLAM and Obstacles Avoidance
•	Utilized OpenCV and Deep Learning to design a vision system for tracking pelvis position over time, resulting in improved accuracy and reliability of robotic systems.

•	Detected obstacles using Lidar technology and built a current map with closed-loop detection, enabling the development of precise and efficient obstacle avoidance control systems.
