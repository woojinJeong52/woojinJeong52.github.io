---
layout: page
title: Research Fields
permalink: /research-fields/
nav: true
nav_order: 4
_styles: >
  .rf-wrap {
    display: grid;
    gap: 1.5rem;
  }
  .rf-grid {
    display: grid;
    gap: 1.5rem;
    grid-template-columns: 1fr;
  }
  @media (min-width: 1200px) {
    .rf-grid {
      grid-template-columns: 1.05fr 1fr;
      align-items: start;
    }
  }
  .rf-col {
    display: grid;
    gap: 1.5rem;
  }
  .rf-section {
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    overflow: hidden;
    background: var(--global-bg-color);
  }
  .rf-title {
    margin: 0;
    padding: 0.85rem 1.1rem;
    background: #223b63;
    color: #fff !important;
    font-size: 1.45rem;
    font-weight: 700;
    line-height: 1.25;
  }
  .rf-body {
    padding: 1rem 1.1rem 1.2rem;
  }
  .rf-body p,
  .rf-body li {
    font-size: 1rem;
    line-height: 1.55;
    margin-bottom: 0.55rem;
  }
  .rf-body ul {
    margin: 0 0 0.7rem 1.2rem;
    padding: 0;
  }
  .rf-label {
    margin: 0.8rem 0 0.4rem;
    font-weight: 700;
  }
  .rf-caption {
    margin: 0.55rem 0 0.7rem;
    font-weight: 700;
    line-height: 1.4;
  }
  .rf-subcaption {
    margin: 0.45rem 0 0;
    line-height: 1.45;
  }
  .rf-figure {
    margin: 0.7rem 0;
  }
  .rf-figure img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    display: block;
  }
---

<div class="rf-wrap">
  <div class="rf-grid">
    <div class="rf-col">
      <section class="rf-section">
        <h2 class="rf-title">Optimal Control and Game Theory Applications</h2>
        <div class="rf-body">
          <div class="rf-figure">
            <img src="{{ '/assets/img/111.png' | relative_url }}" alt="Mean-field game theory summary" loading="lazy" />
          </div>

          <p>Control multiple agents in a decentralized manner through mean-field game theory, utilizing the pre-computed optimal strategy g*</p>

          <div class="rf-figure">
            <img src="{{ '/assets/img/22.png' | relative_url }}" alt="Two-wheeled unmanned vehicle differential game results" loading="lazy" />
          </div>
          <p class="rf-caption">[Distributed Optimal Control of Two-Wheeled Unmanned Vehicles: Differential Game Approach]</p>
          <p>Developed and applied mean-field differential game theory for distributed non-cooperative optimal control of partially observed large-scale two-wheeled unmanned vehicles</p>

          <div class="rf-figure">
            <img src="{{ '/assets/img/33.png' | relative_url }}" alt="Leader follower operation experiments" loading="lazy" />
          </div>

          <div class="rf-figure">
            <img src="{{ '/assets/img/44.png' | relative_url }}" alt="Hexarotor stackelberg game results" loading="lazy" />
          </div>
          <p class="rf-caption">[Distributed Optimal Control of Hexarotor: Stackelberg Game Approach]</p>
          <p>Applied partially observed mean-field Stackelberg game theory for leader-follower distributed optimal flight control of large-scale hexarotor groups</p>

          <div class="rf-figure">
            <img src="{{ '/assets/img/55.png' | relative_url }}" alt="Hexarotor trajectory and error convergence" loading="lazy" />
          </div>
        </div>
      </section>
    </div>

    <div class="rf-col">
      <section class="rf-section">
        <h2 class="rf-title">Reinforcement Learning and Machine Learning Theory and Applications</h2>
        <div class="rf-body">
          <div class="rf-figure">
            <img src="{{ '/assets/img/66.png' | relative_url }}" alt="SACHER algorithm and UAV path planning results" loading="lazy" />
          </div>
          <p class="rf-caption">[Reinforcement Learning-Based SACHER Algorithm for UAV Path Planning and Collision Avoidance]</p>

          <div class="rf-figure">
            <img src="{{ '/assets/img/77.png' | relative_url }}" alt="Active management and load shedding control results" loading="lazy" />
          </div>
          <p class="rf-caption">[Reinforcement Learning-Based Active Management of Power Systems and Emergency Load Shedding Control]</p>

          <div class="rf-figure">
            <img src="{{ '/assets/img/88.png' | relative_url }}" alt="Multi objective RL and maximum norm minimization" loading="lazy" />
          </div>
          <p class="rf-caption">[Single-Policy-Based Multi-Objective Reinforcement Learning: Maximum Norm Minimization Method for Expanding the Pareto Front]</p>
        </div>
      </section>

      <section class="rf-section">
        <h2 class="rf-title">Autonomous Driving and Intelligent Robot Control</h2>
        <div class="rf-body">
          <div class="rf-figure">
            <img src="{{ '/assets/img/99.png' | relative_url }}" alt="Robot platforms" loading="lazy" />
          </div>
          <p class="rf-subcaption">Research and Implementation of Intelligent Control Algorithms Based on Various Robot Platforms</p>

          <div class="rf-figure">
            <img src="{{ '/assets/img/101.png' | relative_url }}" alt="ERP-42 driving experiments and simulation" loading="lazy" />
          </div>
          <p class="rf-subcaption">Development and Validation of Autonomous Driving Algorithms for ERP-42 Vehicle Using Various Sensor Fusion Technologies</p>
        </div>
      </section>
    </div>
  </div>
</div>
