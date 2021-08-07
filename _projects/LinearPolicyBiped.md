---
title: Learning Controllers for Robust Blind Bipedal Locomotion on Challenging Terrains

description: |
  This paper presents a linear policy approach to achieve blind bipedal walking on challenging terrains.
people:
  - lokesh
  - utkarsh
  - shishir

layout: project
image: "/img/IROS_2021.gif"
last-updated: 2021-08-07
---

<br>
#### Abstract
In this paper, with a view toward deployment of  light-weight control frameworks for bipedal walking robots, we realize end-foot trajectories that are shaped by a single linear feedback policy. We learn this policy via a model-free and a gradient free learning algorithm, Augmented Random Search (ARS), in the two robot platforms Rabbit and Digit. Our contributions are two-fold: a) By using torso and support plane orientation as inputs, we achieve robust walking on slopes of upto 20 degree in simulation. b) We demonstrate additional behaviors like walking backwards, stepping-in-place, and recovery from external pushes of upto 120 N. The end-result is a robust and a fast feedback control law for bipedal walking on terrains with varying slopes. Towards the end, we also provide preliminary results of hardware transfer to Digit.
 

<div style="padding-left:50px" class="row">
<div class="column">
        <figure>  
        <img style="padding:5px" src="{{site.base}}/img/lpb_incline.gif" alt="incline" width="250" height="190"/>
        <figcaption style="text-align:center"> Slope: Incline </figcaption>
        </figure>
 </div>
  
 <div class="column">
        <figure>
        <img style="padding:5px" src="{{site.base}}/img/lpb_decline.gif" alt="decline" width="250" height="190"/>
        <figcaption style="text-align:center"> Slope: Decline </figcaption>
        </figure>
  </div>

  <div class="column">
        <figure>
        <img style="padding:5px" src="{{site.base}}/img/lpb_vslope.gif" alt="vslope" width="250" height="190"/>
        <figcaption style="text-align:center"> Variying Slope </figcaption>
        </figure>
    </div>

   <div class="column">
        <figure>
        <img style="padding:5px" src="{{site.base}}/img/lpb_sine.gif" alt="sine" width="250" height="190"/>
        <figcaption style="text-align:center"> Sinusoidal Terrain </figcaption>
        </figure>
    </div>
    
  <div class="column">
        <figure>
        <img style="padding:5px" src="{{site.base}}/img/lpb_spike.gif" alt="spike" width="250" height="190"/>
        <figcaption style="text-align:center"> Undulated-Spiky Terrain </figcaption>
        </figure>
    </div>
        
  <div class="column">
        <figure>
        <img style="padding:5px" src="{{site.base}}/img/lpb_steps.gif" alt="steps" width="250" height="190"/>
        <figcaption style="text-align:center"> Undulated-Step Terrain </figcaption>
        </figure>
    </div>
    
  <div class="column">
        <figure>
        <img style="padding:5px" src="{{site.base}}/img/lpb_stairs.gif" alt="stairs" width="250" height="190"/>
        <figcaption style="text-align:center"> Staircase </figcaption>
        </figure>
    </div>

  <div class="column">
        <figure>
        <img style="padding:5px" src="{{site.base}}/img/lpb_omnidircect.gif" alt="omni" width="250" height="190"/>
        <figcaption style="text-align:center"> Omni-Driectional Walking </figcaption>
        </figure>
    </div>

</div>
<br>
## Controller Framework
<div style="text-align:center">
<img src="{{site.base}}/img/IROS_21_BipedControlArchv2.png" alt="drawing" height="253" width="800"/>
</div>
<br>
## Video
<br>
<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/4WhgD8u74OY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
<br>

<br/>
## Citation ##
```
    @misc{krishna2021learning,
        title={Learning Linear Policies for Robust Bipedal Locomotion on Terrains with Varying Slopes}, 
        author={Lokesh Krishna and Utkarsh A. Mishra and Guillermo A. Castillo and Ayonga Hereid and Shishir Kolathaya},
        year={2021},
        eprint={2104.01662},
        archivePrefix={arXiv},
        primaryClass={cs.RO}
}
```
<br>
<br/>

