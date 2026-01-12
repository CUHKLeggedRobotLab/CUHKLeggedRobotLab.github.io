---
layout: splash
classes:
  - landing
  - dark-theme
title: "Research"
permalink: /research/
---

<style>
.page__content h1 { font-size: 30px; }
.page__content h2 { font-size: 24px; }

/* ===== Research cards (ONLY this page) ===== */
.page__content .research-card{
  display: grid;
  grid-template-columns: 380px 1fr;  /* left image, right text */
  gap: 30px;
  align-items: start;
  margin: 18px 0 34px 0;
}

.page__content .research-media{
  width: 100%;
}

.page__content .research-media img{
  width: 100%;
  border-radius: 10px;
  display: block;
}

.page__content .research-text p{
  font-size: 14pt;
  margin: 0 0 12px 0;
  text-align: justify;
}

.page__content .research-topics{
  font-size: 14pt;
  margin: 0 0 12px 0;
}

.page__content .research-meta{
  margin-top: 14px;
  padding: 14px 18px;
  background: #f6f6f6;
  border-left: 4px solid #999;
  border-radius: 10px;
  font-size: 13.5pt;
  line-height: 1.6;
}

.page__content .research-meta-grid{
  display: grid;
  grid-template-columns: 110px 1fr;
  row-gap: 6px;
}

.page__content .research-links a{
  text-decoration: none;
}

@media (max-width: 900px){
  .page__content .research-card{
    grid-template-columns: 1fr;
    gap: 16px;
  }
  .page__content .research-meta-grid{
    grid-template-columns: 90px 1fr;
  }
}
</style>


<br>


# Ongoing Research
## Robust and Precise Locomotion for Legged Robots
<div class="research-card">

  <!-- Left: Image -->
  <div class="research-media">
    <img src="/assets/images/research/robust_precise_locomotion.png"
         alt="Robust and Precise Locomotion">
  </div>

  <!-- Right: Text -->
  <div class="research-text">
    <p>
      This ongoing research aims to enable robust and precise locomotion across diverse and unstructured terrains by leveraging reinforcement learning and imitation learning in conjunction with environment-aware perception. The goal is to develop learning-based locomotion policies that can adapt to terrain variations and external disturbances while maintaining accurate foot placement and stable motion execution. By combining imitation learning for structured motion priors with reinforcement learning for online adaptation, we seek to improve tracking accuracy, contact reliability, and robustness under significant environmental uncertainty. Ultimately, this research is expected to advance the deployment of legged robots in real-world environments requiring both precision and resilience.
    </p>
    <div class="research-topics">
      Topics: legged locomotion / reinforcement learning / imitation learning
    </div>
  </div>

</div>

## Environment-aware Perception and Navigation
<div class="research-card">

  <!-- Left: Image -->
  <div class="research-media">
    <img src="/assets/images/research/environment_aware_navigation.png"
         alt="Environment-aware Perception and Navigation">
  </div>

  <!-- Right: Text -->
  <div class="research-text">
    <p>
      This research focuses on developing environment-aware perception and navigation methods tailored
      for legged robotic systems, enabling autonomous navigation in dynamic and extreme terrains.
      By leveraging onboard sensing and real-time environment assessment, the robot can reason about
      terrain geometry, traversability, and environmental changes without relying on pre-built maps.
      The goal is to achieve map-free navigation that allows legged robots to adapt their motion and
      navigation strategies in highly unstructured, cluttered, or rapidly changing environments,
      supporting long-horizon autonomy and robust operation in real-world scenarios.
    </p>
    <div class="research-topics">
      Topics: legged robot navigation / terrain assessment and planning /
      map-free navigation / autonomous systems
    </div>
  </div>

</div>

## Dexterous and Whole-Body Coordinated Loco-Manipulation
<div class="research-card">

  <!-- Left: Image -->
  <div class="research-media">
    <img src="/assets/images/research/loco_manipulation.png"
         alt="Dexterous and Whole-Body Coordinated Loco-Manipulation">
  </div>

  <!-- Right: Text -->
  <div class="research-text">
    <p>
      This research explores dexterous loco-manipulation using quadruped robots equipped with manipulators,
      treating the full robot as a coordinated multi-limb system analogous to a dexterous hand. By exploiting
      contacts from legs, arms, and the robot body, the system can perform complex manipulation tasks that
      require simultaneous mobility, force regulation, and contact switching. The goal is to enable adaptive
      whole-body behaviors through coordinated motion and force control across multiple contact points,
      allowing legged manipulators to robustly interact with the environment in contact-rich and unstructured
      scenarios.
    </p>
    <div class="research-topics">
      Topics: loco-manipulation / multi-contact planning /
      whole-body control / dexterous manipulation
    </div>
  </div>

</div>

## Safe Actuator and Mechanical System Design

<div class="research-card">

  <!-- Left: Image -->
  <div class="research-media">
    <img src="/assets/images/research/safe_actuator_design.png"
         alt="Safe Actuator and Mechanical System Design">
  </div>

  <!-- Right: Text -->
  <div class="research-text">
    <p>
      This research focuses on safety-oriented actuator and mechanical system design for legged robots,
      aiming to ensure reliable operation under highly dynamic and contact-rich conditions. The goal is
      to mitigate risks associated with overshoot, impact forces, vibrations, oscillations, and thermal
      overload in electric actuators and mechanical transmissions. By jointly considering actuation,
      mechanical compliance, sensing, and control-aware design, this work seeks to improve interaction
      safety, durability, and robustness of legged robotic systems, enabling stable and safe deployment
      in real-world environments.
    </p>

    <div class="research-topics">
      Topics: legged robot hardware / safe actuation /
      mechanical design / compliant systems
    </div>
  </div>

</div>



# Completed Research

## Quadruped Jumping Motion Planning and Control
<!-- Meta information box (now placed under the title) -->
<div class="research-meta" style="margin: 12px 0 18px 0;">
  <div class="research-meta-grid">
    <div><b>Director:</b></div>
    <div>Yue Linzhu</div>
    <div><b>Thesis:</b></div>
    <div class="research-links">
      <a href="https://repository.lib.cuhk.edu.hk/en/item/cuhk-3551314?solr_nav%5Bid%5D=effa3150406c6a95a314&solr_nav%5Bpage%5D=0&solr_nav%5Boffset%5D=0"
         target="_blank" rel="noopener">Optimization-based Motion Planning for Agile Legged Locomotion</a>
    </div>
  </div>
</div>

<!-- Image + Text card -->
<div class="research-card">

  <!-- Left: Image -->
  <div class="research-media">
    <img src="/assets/images/research/q_jumping.png" alt="Quadruped Jumping Framework">
  </div>

  <!-- Right: Text -->
  <div class="research-text">
    <p>
      Jumping enables quadruped robots to overcome obstacles and operate in complex, unstructured environments.
      This research develops a motion planning and control framework for quadruped jumping that ensures agility,
      stability, and robustness under kinodynamic and contact constraints. Jumping motions are formulated as
      constrained optimization problems, integrating offline trajectory optimization with online tracking and
      model predictive control to handle disturbances and uncertainties. Simulation and hardware experiments
      demonstrate reliable execution of agile jumping behaviors, supporting real-world deployment.
    </p>

    <div class="research-topics">
      Topics: quadruped locomotion / jumping motion planning / optimal control / MPC
    </div>
  </div>

</div>

<br>

## Differential Parallel Leg Mechanism for Quadruped Robots
<!-- Meta information box -->
<div class="research-meta" style="margin: 12px 0 18px 0;">
  <div class="research-meta-grid">
    <div><b>Director:</b></div>
    <div>Song Zhitao</div>
    <div><b>Thesis:</b></div>
    <div><i>Co-Design Optimization of Legged Robots for Payload and Energy Efficiency</i></div>
  </div>
</div>

<!-- Image + Text card -->
<div class="research-card">

  <!-- Left: Image -->
  <div class="research-media">
    <img src="/assets/images/research/tmech_2025_three_segment_leg.png"
         alt="Differential Parallel Leg Mechanism">
  </div>

  <!-- Right: Text -->
  <div class="research-text">
    <p>
      This research investigates a novel differential parallel leg mechanism for quadruped robots,
      aiming to achieve high force output with improved energy efficiency. By coupling multiple actuators
      through a differential parallel architecture, the design enables load sharing and effective
      utilization of passive elastic elements, reducing peak motor torque and overall energy consumption.
      Simulation studies and prototype evaluations demonstrate enhanced force capability and
      energy-efficient performance during dynamic locomotion tasks.
    </p>

    <div class="research-topics">
      Topics: quadruped robots / parallel leg mechanisms / differential actuation /
      energy-efficient design
    </div>
  </div>

</div>