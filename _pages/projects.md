---
layout: page
title: Projects
permalink: /projects/
# description: A growing collection of your cool projects.
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

For more videos, you are welcome to visit my [Youtube channel](https://www.youtube.com/channel/UCAduhzSeh_5dEN9CteFiM9w).
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/project/Tinghua_work.jfif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br />

---

#### Source-seeking Robot [(PDF)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458274&tag=1)
 In this work, we present the design and experimental validation of source-seeking control algorithms for a unicycle mobile robot that is equipped with novel 3-D-printed flexible graphene-based piezoresistive airflow sensors. Based solely on a local gradient measurement from the airflow sensors, we propose and analyze a projected gradient ascent algorithm to solve the source-seeking problem. In the case of partial sensor failure, we
propose a combination of extremum-seeking control with our projected gradient ascent algorithm. For both control laws, we prove the asymptotic convergence of the robot to the source. 
<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.html path="/assets/video/SS.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>


<br />

---

#### CBF-based collision avoidance control [(PDF)](https://arxiv.org/pdf/2212.07203.pdf)
In this work, we propose a collision-free source seeking control framework for unicycle robots traversing an unknown cluttered environment. In this framework, the obstacle avoidance is guided by the control barrier functions (CBF) embedded in quadratic programming and the source seeking control relies solely on the use of on-board sensors that measure signal strength of the source. To tackle the mixed relative degree of the CBF, we proposed three different CBF, namely the zeroing control barrier functions (ZCBF), exponential control barrier functions (ECBF), and reciprocal control barrier functions (RCBF) that can directly be integrated with our recent gradient-ascent sourceseeking control law. 
<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.html path="/assets/video/CO.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>



<br />

---

#### Flocking Control of multi-agents with connectivity preservation [(PDF)](https://arxiv.org/pdf/2301.04576.pdf)
 We present a distributed source seeking and flocking control method for networked multi-agent systems with nonholonomic constraint in an unknown cluttered environment. Based solely on identical on-board sensor systems, which measure the source local field, the group objective is attained by appointing a leader agent, which has the largest signal strength to the source (as a proxy to the distance to the source), to seek the source while the remaining follower agents form a cohesive flocking with the leader using a distributed flocking control law
in a connectivity-preserved undirected network of multi-agent systems. To guarantee the safe separation and group motion for all agents and to solve the conflicts with the ”cohesion” flocking rule of Reynolds, the distributed control algorithm is solved individually through quadratic-programming optimization problem with safety constraints, which guarantee the collision avoidance for inter-agents and obstacles in the cluttered environment. 
<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.html path="/assets/video/connectivity.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

<br />

---

#### Flexible Distributed Flocking Control for Multi-agent Unicycle Systems [(PDF)](https://arxiv.org/pdf/2308.04127.pdf)
 Currently, the general aim of flocking and formation control laws for multi-agent systems is to form and maintain a rigid configuration, such as, the alpha-lattices in flocking control methods, where the desired distance between each pair of connected agents is fixed. This introduces a scalability issue for large-scale deployment of agents due to unrealizable geometrical constraints and the constant need of centralized orchestrator to ensure the formation graph rigidity. This paper presents a flexible distributed flocking cohesion algorithm for nonholonomic multi-agent systems. The desired geometry configuration between each pair of agents is adaptive and flexible. The distributed flocking goal is achieved using limited information exchange (i.e., the local field gradient) between connected neighbor agents and it does not rely on any other motion variables measurements, such as (relative) position, velocity, or acceleration. Additionally, the flexible flocking scheme with safety is considered so that the agents with limited sensing capability are able to maintain the connectedness of communication topology at all time and avoid inter-agent collisions. The stability analysis of the proposed methods is presented along with numerical simulation results to show their effectiveness.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/pub/flex_flock/static_initial_graph_complete.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/pub/flex_flock/static_final_graph.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/pub/flex_flock/dynamic_initial_graph.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pub/flex_flock/dynamic_final_graph.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
