---
layout: page
permalink: /Ph.D. thesis/
title: Ph.D. Thesis
description: 
nav: true
nav_order: 5
 
---
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
          {% include figure.liquid loading="eager" path="/assets/img/cover-all.png" title="example image" class="img-fluid rounded z-depth-1" %}
          </div>
</div>

#### [Motion control for nonholonomic unicycle robots (abstract)](https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots)
- With the rapid development of perception, communication and computation technologies and the increasing requirements on safety-critical systems, autonomous robots must be able to safely achieve missions in a hazardous environment and to cope with difficult situations. Such safety-critical tasks require smart motion control strategies to address complex constraints and to navigate in cluttered scenarios. However, the motion control for nonholonomic wheeled mobile robots is challenging as they are subject to the kinematic constraint which limits sideway movements. This restriction makes traditional control methods insufficient for precise motions, and it poses challenges in navigating cluttered environment safely.

- This doctoral research focuses on developing algorithms for nonholonomic robots in an unknown cluttered scenario, where the robot solely relies on the limited onboard sensory measurements for exploration. Part I aims to bridge the gap between perception and control tasks, by introducing the projected gradient-ascent source-seeking control and safety guarantee for a single robot traversing an unknown signal field where random obstacles exist. The main contributions lie in the control design with asymptotic convergence analysis and the CBF design with uniform relative degree. The results are extended to the multi-agent system in Part II, where a distributed CBF-QP framework is proposed for achieving collision avoidance and maintaining connectivity preservation in flocking cohesion control problem, and an adaptive spacing policy is presented for flexible coordination. In summary, this doctoral thesis contributes to novel (distributed) control algorithms for nonholonomic robots that warrant four control systems properties: safety guarantee, configuration stabilization, optimization feasibility, and group behavior flexibility. 
<br>



#### Chapter: Source-seeking control with nonholonomic constraint
- The first project ``source-seeking of a unicycle robot in an unknown signal field" draws inspiration from the bacterial chemotaxis and the navigation of Mexican tetra in the darkness. This project bridges the gap between the limited local perception and motion task through a time-continuous projected gradient-ascent control law. In contrast to conventional gradient-based methods that limit control to a single motion variable to prevent nonholonomic constraint violations, our approach enhances motion flexibility by offering the unique ability to concurrently control both longitudinal and angular velocities, and relax the bound restriction of the gradient’s curvature. Moreover, the method can be easily integrated with the typical extremum-seeking-control (ESC) for facilitating fault-tolerant tasks and it can make contributions to hazardous missions in physical signal fields (e.g., fire fighting and rescue, exit search, chemical leakage exploration ). The efficacy is verified in experiments where novel 3D-printed graphene-based piezoresistive airflow sensors are deployed for signal measurements in the uncertain airflow field, so as to imitate the cilia bundles perception of blind cavefish.
<br>


#### Chapter: Safety with control barrier function
- Subsequently, to investigate the control mission in an unknown obstacle-occupied signal field, the safety maintenance problem is imposed. Without mapping information known a priori, the control problem is formulated as optimization with safety constraints, where only the relative distance and bearing angle with respect to the closest obstacle are required. For addressing the mixed relative degree problem within the implementation of control barrier functions (CBF) for unicycle robots, three various CBF construction strategies are proposed. Particularly, the relative degree is uniformed into 1 through the distance & bearing-based zeroing control barrier function, which is constructed with an extended state space. The proposed method does not change the dynamics of the robot and provides better accuracy in safety-critical scenarios (no offset point needs to be assigned on the robot's frame as in typical solutions).<br>
<br>

#### Chapter: Group flocking, connectivity preservation and safety
- Building upon the fundamentals established for a single nonholonomic unicycle robot, we expand our control analysis to multi-unicycle systems that involve additional constraints. In the coordination of nonholonomic robots, a new scheme of flocking cohesion and controller is proposed, which does not use the typical feedback linearization and avoids the approximation error. Next, the above CBF-based optimization method is extended to address the connectivity maintenance and inter-agent safety of multi-unicycles, where a distributed ZCBF with extended state space is designed for each nonholonomic agent with respect to its connected neighbors in the maximum sensing hood. As an extra contribution, to reduce the infeasibility problem due to the conflicts between dense inter-agent constraints, an updated weight parameter is engaged on the extended class K  function such that the intersection of admissible sets can be guaranteed. The distributed quadratic programming framework is applicable to a broad range of constraint-driven problems, demonstrating its effectiveness in both static and dynamic topologies.
<br>

#### Chapter: Adaptive spacing policy in flexible coordination
- In the typical group aggregation and cohesion problems, the desired collective configuration is defined as a rigid structure where each agent is equally distanced from all of its neighbors (e.g., the alpha-lattices). Practically, this introduces a scalability issue for large-scale deployment of agents due to unrealizable geometrical constraints and the constant need for a centralized orchestrator to ensure graph rigidity. Hence, I propose an adaptive spacing policy (ASP) and a flexible distributed flocking cohesion algorithm for nonholonomic multi-agent systems, where the desired geometry configuration between each pair of agents is adaptive and flexible.  Additionally, safety requirement is integrated so that the agents with limited sensing capability are able to maintain the connectedness of communication topology at all time and avoid inter-agent collisions. 
<br>

### Acknowledge 
- I would like to thank my dearest supervisor **Prof. Bayu Jayawardhana** and **Prof. Ming Cao** for their warm support in the past four-year study, thank  **Simon Busman** and **Wouter Baar** for being my best paranymphs, thank my lovely colleagues and friends in DTPA group. Thank you for all defense committee members for the great discussion during the defense: **Claudio De Persis, Dimos Dimarogonas, Tamas Keviczky, Raffaella Carloni, Maryam Ghandchi Tehrani, Sami Haddadin, Bahar Haghighat, Ashish Cherukuri**. <a href="/assets/img/pdf/acknowledgment.pdf"  target = "_blank"> My full acknowledge is here. </a>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
          {% include figure.liquid loading="eager" path="/assets/img/news/phd.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
          </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/news/phd_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}    
        </div>
      <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/news/phd_3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}    
        </div>
</div>

<br>

<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.liquid path="/assets/video/defence.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
