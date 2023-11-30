---
title: Stoch BiRo

description: |
  Design and Control of a low cost bipedal robot
  
people:
  - manan
  - karthikraj
  - ravikola
  - mothish

layout: project
image: "/img/dridh.png"
last-updated: 2023-12-01
---
### Abstract 
In this paper, we present a complete description of the hardware design and control architecture of our custom built bipedal robot, called the Stoch BiRo. Our goal is to realize a robust, modular, and a reliable Bipedal platform, using which various locomotion behaviors are explored.


### Design and Development of Stoch BiRo
We present a complete description of the hardware design and control architecture of our custom built quadruped robot, called the Stoch. Our goal is to realize a robust, modular, and a reliable quadrupedal platform, using which various locomotion behaviors are explored. This platform enables us to explore different research problems in legged locomotion, which use both traditional and learning based techniques. We discuss the merits and limitations of the platform in terms of exploitation of available behaviours, fast rapid prototyping, reproduction and repair.

### Control Framework 
We use a hierarchical structure, that decouples the linear and nonlinear parts of the control framework. The linear part is the foot trajectory modulator, and the nonlinear part is the tracking controller. Based on the orientation of torso and supporting plane, the modulator transforms the semi-ellipses in real-time. The tracking controller then tracks the generated semi-ellipses independently for each leg with a constant phase difference.
Joint-level PD controllers are used to track the required joint targets obtained through inverse kinematics. Note that our controller does not include contact modelling and explicit switching conditions, as a model-free learning algorithm
is used.
