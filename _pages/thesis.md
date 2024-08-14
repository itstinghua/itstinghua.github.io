---
layout: page
permalink: /Ph.D. thesis/
title: Ph.D. Thesis
description: 
nav: true
nav_order: 5
 
---
- **Motion control for nonholonomic unicycle robots** ([The full-text version can be found here.](https://research.rug.nl/en/publications/motion-control-for-nonholonomic-unicycle-robots))
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
          {% include figure.liquid loading="eager" path="/assets/img/cover-all.png" title="example image" class="img-fluid rounded z-depth-1" %}
          </div>
</div>
<center class="half">
    <img src="/assets/img/cover-all.png"" width="500"/>
</center>

<br>

#### Abstract 
- With the rapid development of perception, communication and computation technologies and the increasing requirements on safety-critical systems, autonomous robots must be able to safely achieve missions in a hazardous environment and to cope with difficult situations. Such safety-critical tasks require smart motion control strategies to address complex constraints and to navigate in cluttered scenarios. However, the motion control for nonholonomic wheeled mobile robots is challenging as they are subject to the kinematic constraint which limits sideway movements. This restriction makes traditional control methods insufficient for precise motions, and it poses challenges in navigating cluttered environment safely.
<br>
<br>
This doctoral research focuses on developing algorithms for nonholonomic robots in an unknown cluttered scenario, where the robot solely relies on the limited onboard sensory measurements for exploration. Part I aims to bridge the gap between perception and control tasks, by introducing the projected gradient-ascent source-seeking control and safety guarantee for a single robot traversing an unknown signal field where random obstacles exist. The main contributions lie in the control design with asymptotic convergence analysis and the CBF design with uniform relative degree. The results are extended to the multi-agent system in Part II, where a distributed CBF-QP framework is proposed for achieving collision avoidance and maintaining connectivity preservation in flocking cohesion control problem, and an adaptive spacing policy is presented for flexible coordination. In summary, this doctoral thesis contributes to novel (distributed) control algorithms for nonholonomic robots that warrant four control systems properties: safety guarantee, configuration stabilization, optimization feasibility, and group behavior flexibility. 
<br>

### Acknowledgment 
- I would like to thank my dearest supervisor **Prof. Bayu Jayawardhana** and **Prof. Ming Cao** for their warm support in the past four-year study, thank  **Simon Busman** and **Wouter Baar** for being my best paranymphs, thank my lovely colleagues and friends in DTPA group. Thank you for all defense committee members for the great discussion during the defense: **Prof. Claudio De Persis, Prof. Dimos Dimarogonas, Prof. Tamas Keviczky, Prof. Raffaella Carloni, Prof. Maryam Ghandchi Tehrani, Prof. Sami Haddadin, Dr. Bahar Haghighat, Dr. Ashish Cherukuri**. <a href="/assets/pdf/acknowledge.pdf"  target = "_blank"> My full acknowledgment is here. </a>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
          {% include figure.liquid loading="eager" path="/assets/img/news/phd_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
          </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/news/phd.jpg" title="example image" class="img-fluid rounded z-depth-1" %}    
        </div>
      <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/news/phd_3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}    
        </div>
</div>

<div class="row mt-2">
    <div class="col-sm mt-2 mt-md-0">
        {% include video.liquid path="/assets/video/defence.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
