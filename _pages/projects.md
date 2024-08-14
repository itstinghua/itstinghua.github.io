---
layout: page
title: Projects
permalink: /projects/
description:
nav: true
nav_order: 2
display_categories: 
horizontal: 
---

For more videos, you are welcome to visit my [Youtube channel](https://www.youtube.com/channel/UCAduhzSeh_5dEN9CteFiM9w).
<center class="half">
    <img src="/assets/video/tinghua.gif" width="600"/>
</center>


---
#### [Source-seeking Robot](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458274&tag=1)
We present the design and experimental validation of source seeking control algorithms for a unicycle mobile robot that is equipped with novel 3D-printed flexible graphene-based piezoresistive airflow sensors. Based solely on a local gradient measurement from the airflow sensors, we propose and analyze a projected gradient ascent algorithm to solve the source seeking problem. In the case of partial sensor failure, we propose a combination of Extremum-Seeking Control with our projected gradient ascent algorithm. For both control laws, we prove the asymptotic convergence of the robot to the source. Numerical simulations were performed to validate the algorithms and experimental validations are presented to demonstrate the efficacy of the proposed methods.
<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.liquid path="/assets/video/SS.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

<br />

---

#### [CBF-based collision avoidance control](https://arxiv.org/pdf/2212.07203.pdf)
In this work, we propose a collision-free source-seeking control framework for unicycle robots traversing an unknown cluttered environment. In this framework, obstacle avoidance is guided by the control barrier functions (CBF) embedded in quadratic programming and the source seeking control relies solely on the use of on-board sensors that measure the signal strength of the source. To tackle the mixed relative degree of the CBF, we proposed three different CBFs, namely the zeroing control barrier functions (ZCBF), exponential control barrier functions (ECBF), and reciprocal control barrier functions (RCBF)  that can directly be integrated with our recent gradient-ascent source-seeking control law. We provide rigorous analysis of the three different methods and show the efficacy of the approaches in simulations using Matlab, as well as, using a realistic dynamic environment with moving obstacles in Gazebo/ROS. 
 <div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.liquid path="/assets/video/CO.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<br />

---

#### [Flocking Control of multi-agents with connectivity preservation](https://arxiv.org/pdf/2301.04576.pdf)
We present a distributed source-seeking and flocking control method for networked multi-agent systems with non-holonomic constraints. Based solely on identical on-board sensor systems, which measure the source local field, the group objective is attained by appointing a leader agent to seek the source while the remaining follower agents form a cohesive flocking with their neighbors using a distributed flocking control law in a connectivity-preserved undirected network. To guarantee the safe separation and group motion for all agents and to solve the conflicts with the "cohesion" flocking rule of Reynolds, the distributed control algorithm is solved individually through quadratic-programming optimization problem with constraints, which guarantees the inter-agent collision avoidance and connectivity preservation. Stability analysis of the closed-loop system is presented and the efficacy of the methods is shown in simulation results. 
<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.liquid path="/assets/video/connectivity.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

<br />

---

#### Flexible Distributed Flocking Control 
Currently, the general aim of flocking and formation control laws for multi-agent systems is to form and maintain a rigid configuration, such as the alpha-lattice in flocking control methods, where the desired distance between each pair of connected agents is constant and fixed. This introduces a scalability issue for large-scale deployment of agents due to unrealizable geometrical constraints and the constant need for a centralized orchestrator to ensure the formation graph rigidity. This work proposes an adaptive spacing policy (ASP) to regulate the inter-agent gap, and presents a flexible flocking cohesion control law based on this policy, such that all agents converge to a flexible configuration while not violating their nonholonomic constraints and ensuring the well-posedness of the final flock geometry. The stability analysis and applications of the proposed flexible flocking framework are presented along with numerical simulation results.
<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.liquid path="/assets/video/flexible.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>


<br />