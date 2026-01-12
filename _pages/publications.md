---
layout: splash
classes:
  - landing
  - dark-theme
title: "Publications"
permalink: /publications/
---

<style>
.page__content h1 { font-size: 30px; }
.page__content h2 { font-size: 24px; }

/* ===== Publication cards (ONLY this page) ===== */
.page__content .pub-card{
  display: grid;
  grid-template-columns: 240px 1fr;
  gap: 18px;
  margin: 18px 0 26px 0;
  align-items: start;
}

/* ===== Publication cards (ONLY this page) ===== */
.page__content .pub-media{
  width: 240px;              
  aspect-ratio: 16 / 9;      
  overflow: hidden;
  border-radius: 10px;
  border: 1px solid #ddd;
  background: #f5f5f5;
}

.page__content .pub-media img{
  width: 100%;
  height: 100%;
  object-fit: cover;         
  object-position: center;   
  display: block;
}

.page__content .pub-title{
  font-size: 14pt;
  font-weight: 700;
  line-height: 1.25;
  margin: 0 0 6px 0;
}

.page__content .pub-authors{
  font-size: 14pt;
  margin: 0 0 4px 0;
}

.page__content .pub-venue{
  font-size: 14pt;
  font-style: italic;
  margin: 0 0 8px 0;
}

.page__content .pub-links{
  font-size: 14pt;
}

/* Responsive */
@media (max-width: 820px){
  .page__content .pub-card{
    grid-template-columns: 1fr;
  }
  .page__content .pub-media{
    max-width: 420px;
  }
}
</style>

<br>

## 2025

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/tro_2025_traversability.gif" alt="Traversability-Aware Navigation">
  </div>
  <div>
    <div class="pub-title">Traversability-Aware Legged Navigation by Learning from Real-World Visual Data</div>
    <div class="pub-authors">
      H. Zhang, Z. Li, X. Zeng, L. Smith, K. Stachowicz, … &amp; and Y. H. Liu
    </div>
    <div class="pub-venue">IEEE Transactions on Robotics (<b>T-RO</b>), 2025</div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2410.10621">arXiv</a> |
      <a href="https://www.youtube.com/watch?v=RSqnIWZ1qks">video</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/tmech_2025_three_segment_leg.png" alt="Three-Segment Leg">
  </div>
  <div>
    <div class="pub-title">Codesign of a Differential Three-Segment Leg Enhancing Payload and Efficiency in Quadrupeds</div>
    <div class="pub-authors">
      Z. Song, L. Yue, L. Zhang, X. Zeng, H. Zhang, J. Dong, … &amp; Y. H. Liu
    </div>
    <div class="pub-venue">IEEE/ASME Transactions on Mechatronics (<b>TMECH</b>), 2025</div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/11130397">link</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/iros_2025_robust_mpc.png" alt="Robust MPC">
  </div>
  <div>
    <div class="pub-title">
      Robust Model Predictive Control for Quadruped Locomotion Under Model Uncertainties and External Disturbances
    </div>
    <div class="pub-authors">W. Xia, L. Yue &amp; Y. H. Liu</div>
    <div class="pub-venue">
      IEEE/RSJ International Conference on Intelligent Robots and Systems (<b>IROS</b>), 2025
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/document/11246673">link</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/arxiv_2025_humanoid_wbc.gif" alt="Humanoid WBC">
  </div>
  <div>
    <div class="pub-title">
      Whole-Body Control Framework for Humanoid Robots with Heavy Limbs: A Model-Based Approach
    </div>
    <div class="pub-authors">
      T. Zhang, L. Yue, H. Zhang, L. Zhang, X. Zeng, Z. Song, and Y. H. Liu
    </div>
    <div class="pub-venue">
      <i>arXiv preprint</i>, arXiv:2506.14278, 2025
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2506.14278">arXiv</a> |
      <a href="https://www.youtube.com/watch?v=--KyvVvE7XM&amp;t=3s">video</a>
    </div>
  </div>
</div>

<hr>

## 2024

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/iros_2024_omni_jump.png" alt="Omnidirectional Jumping">
  </div>
  <div>
    <div class="pub-title">
      A Fast Online Omnidirectional Quadrupedal Jumping Framework via Virtual-Model Control and Minimum Jerk Trajectory Generation
    </div>
    <div class="pub-authors">
      L. Yue, L. Zhang, Z. Song, H. Zhang, J. Dong, X. Zeng, &amp; Y. H. Liu
    </div>
    <div class="pub-venue">
      IEEE/RSJ International Conference on Intelligent Robots and Systems (<b>IROS</b>), 2024
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/10802277">link</a> |
      <a href="https://www.youtube.com/watch?v=BH0W5F8D1XI">video</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/icra_2024_adaptive_mpc.png" alt="Adaptive MPC">
  </div>
  <div>
    <div class="pub-title">
      Adaptive Model Predictive Control with Data-driven Error Model for Quadrupedal Locomotion
    </div>
    <div class="pub-authors">
      X. Zeng, H. Zhang, L. Yue, Z. Song, L. Zhang, &amp; Y. H. Liu
    </div>
    <div class="pub-venue">
      IEEE International Conference on Robotics and Automation (<b>ICRA</b>), 2024
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/10611302">link</a> |
      <a href="https://www.youtube.com/watch?v=T2YMT7QSnfA">video</a>
    </div>
  </div>
</div>

<hr>

## 2023

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/iros_2023_evolutionary_jump.png" alt="Evolutionary Jump Planning">
  </div>
  <div>
    <div class="pub-title">
      Evolutionary-Based Online Motion Planning Framework for Quadruped Robot Jumping
    </div>
    <div class="pub-authors">
      L. Yue, Z. Song, H. Zhang, X. Zeng, L. Zhang, &amp; Y. H. Liu
    </div>
    <div class="pub-venue">
      IEEE/RSJ International Conference on Intelligent Robots and Systems (<b>IROS</b>), 2023
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/10342082">link</a> |
      <a href="https://www.youtube.com/watch?v=oDcqd7AUlD0&amp;t=31s">video</a>
    </div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/corl_2023_genloco.png" alt="GenLoco">
  </div>
  <div>
    <div class="pub-title">
      GenLoco: Generalized Locomotion Controllers for Quadrupedal Robots
    </div>
    <div class="pub-authors">
      G. Feng, H. Zhang, Z. Li, X. B. Peng, B. Basireddy, L. Yue, … &amp; S. Levine
    </div>
    <div class="pub-venue">
      Conference on Robot Learning (<b>CoRL</b>), 2023
    </div>
    <div class="pub-links">
      <a href="https://proceedings.mlr.press/v205/feng23a.html">link</a> |
      <a href="https://www.youtube.com/watch?v=5QUs32MjNu4">video</a>
    </div>
  </div>
</div>

<hr>

## 2022

<div class="pub-card">
  <div class="pub-media">
    <img src="/assets/images/publications/iros_2022_optimal_jump.png" alt="Optimal Jump Planning">
  </div>
  <div>
    <div class="pub-title">
      An Optimal Motion Planning Framework for Quadruped Jumping
    </div>
    <div class="pub-authors">
      Z. Song, L. Yue, G. Sun, Y. Ling, H. Wei, L. Gui, &amp; Y. H. Liu
    </div>
    <div class="pub-venue">
      IEEE/RSJ International Conference on Intelligent Robots and Systems (<b>IROS</b>), 2022
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/9981642">link</a> |
      <a href="https://www.youtube.com/watch?v=zM-GijBoszc">video</a>
    </div>
  </div>
</div>
