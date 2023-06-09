---
title: Dridh Bipedal Robot

description: |
  Design, development and experimental realisation of a Bipedal Robot research platform: Dridh
  
people:
  - manan
  - karthikraj
  - ravikola
  - mothish

layout: project
image: "/img/dridh.png"
last-updated: 2023-06-08
---
### Abstract 
In this paper, we present a complete description of the hardware design and control architecture of our custom built bipedal robot, called the Dridh. Our goal is to realize a robust, modular, and a reliable Bipedal platform, using which various locomotion behaviors are explored.


### Design and Development of Dridh
We present a complete description of the hardware design and control architecture of our custom built quadruped robot, called the Stoch. Our goal is to realize a robust, modular, and a reliable quadrupedal platform, using which various locomotion behaviors are explored. This platform enables us to explore different research problems in legged locomotion, which use both traditional and learning based techniques. We discuss the merits and limitations of the platform in terms of exploitation of available behaviours, fast rapid prototyping, reproduction and repair.

### Control Framework 
We use a hierarchical structure, that decouples the linear and nonlinear parts of the control framework. The linear part is the foot trajectory modulator, and the nonlinear part is the tracking controller. Based on the orientation of torso and supporting plane, the modulator transforms the semi-ellipses in real-time. The tracking controller then tracks the generated semi-ellipses independently for each leg with a constant phase difference.
Joint-level PD controllers are used to track the required joint targets obtained through inverse kinematics. Note that our controller does not include contact modelling and explicit switching conditions, as a model-free learning algorithm
is used.

<!-- <br/>
<img src="{{site.base}}/img/tile_backtrot.png" alt="drawing" width="600"/>
<img src="{{site.base}}/img/tile_sidestep.png" alt="drawing" width="600"/>
<img src="{{site.base}}/img/tile_turn.png" alt="drawing" width="600"/>

[![Gait Library Synthesis](http://i3.ytimg.com/vi/3BQYX2vZdAg/hqdefault.jpg)](https://www.youtube.com/watch?v=3BQYX2vZdAg&t=97s&ab_channel=Stoch_IISc "GaitLibrary")
[![Learning Stable Manuveuers](http://i3.ytimg.com/vi/LRbHetp0dcg/hqdefault.jpg)](https://www.youtube.com/watch?v=LRbHetp0dcg&t=15s&ab_channel=kartikpaigwar "ROMAN")

<br/>
## Citation ##
```
        @article{tirumala2019gait,
          title={Gait Library Synthesis for Quadruped Robots via Augmented Random Search},
          author={Tirumala, Sashank and Sagi, Aditya and Paigwar, Kartik and Joglekar, Ashish and Bhatnagar, Shalabh and Ghosal, Ashitava and Amrutur, Bharadwaj and Kolathaya, Shishir},
          journal={arXiv preprint arXiv:1912.12907},
          year={2019}
        }
        
        @article{tirumala2020learning,
          title={Learning Stable Manoeuvres in Quadruped Robots from Expert Demonstrations},
          author={Tirumala, Sashank and Gubbi, Sagar and Paigwar, Kartik and Sagi, Aditya and Joglekar, Ashish and Bhatnagar, Shalabh and Ghosal, Ashitava and Amrutur, Bharadwaj and Kolathaya, Shishir},
          journal={arXiv preprint arXiv:2007.14290},
          year={2020}
        }
        
```
<br/> -->