---
title: Learning a formally verified CBF in stochastic environment

description: |
  Neural Network Based CBF with completeness guarantees
  
people:
  - manan
  - pushpak
  - andrewclark
  - shishir

layout: project
last-updated: 2024-07-27
---
### Learning a formally verified CBF in stochastic environment

Safety is a fundamental requirement of control systems. Control Barrier Functions (CBFs) are proposed to ensure the safety of the control system by constructing safety filters or synthesizing control inputs. However, the safety guarantee and performance of safe controllers rely on the construction of valid CBFs. Inspired by universal approximatability, CBFs are represented by neural networks, known as neural CBFs (NCBFs). This paper presents an algorithm for synthesizing formally verified continuous-time neural Control Barrier Functions in stochastic environments in a single step. The proposed training process ensures efficacy across the entire state space with only a finite number of data points by constructing a sample-based learning framework for Stochastic Neural CBFs (SNCBFs). Our methodology eliminates the need for post hoc verification by enforcing Lipschitz bounds on the neural network, its Jacobian, and Hessian terms. We demonstrate the effectiveness of our approach through case studies on the inverted pendulum system and obstacle avoidance in autonomous driving, showcasing larger safe regions compared to baseline methods.

<br/>
## Citation ##
```
        @article{tayal2024learning,
          title={Learning a Formally Verified Control Barrier Function in Stochastic Environment},
          author={Tayal, Manan and Zhang, Hongchao and Jagtap, Pushpak and Clark, Andrew and Kolathaya, Shishir},
          journal={arXiv preprint arXiv:2403.19332},
          year={2024}
        }
        
```
