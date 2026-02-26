---
layout: page
title: Research Fields
permalink: /research-fields/
nav: true
nav_order: 4
_styles: >
  .rf-wrap {
    display: grid;
    gap: 2rem;
  }
  .rf-section {
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    overflow: hidden;
    background: var(--global-bg-color);
  }
  .rf-title {
    margin: 0;
    padding: 0.9rem 1.2rem;
    background: #223b63;
    color: #ffffff !important;
    font-size: 1.55rem;
    font-weight: 700;
  }
  .rf-body {
    padding: 1.2rem 1.2rem 1.4rem 1.2rem;
  }
  .rf-body p,
  .rf-body li {
    font-size: 1.02rem;
    line-height: 1.55;
  }
  .rf-subtitle {
    margin: 1.1rem 0 0.5rem 0;
    font-size: 1.2rem;
    font-weight: 700;
  }
  .rf-block {
    margin-top: 1rem;
    padding-top: 1rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .rf-placeholder {
    margin-top: 0.8rem;
    padding: 1.1rem;
    border: 1px dashed var(--global-divider-color);
    border-radius: 6px;
    text-align: center;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
  }
---

<div class="rf-wrap">
  <section class="rf-section">
    <h2 class="rf-title">Optimal Control and Game Theory Applications</h2>
    <div class="rf-body">
      <p class="rf-subtitle">Core Topics</p>
      <ul>
        <li>Mean-field game theory for large-scale multi-agent systems</li>
        <li>Pre-computable optimal strategy approximation for distributed control</li>
        <li>Decentralized control with local state-based decision making</li>
      </ul>

      <div class="rf-block">
        <p class="rf-subtitle">Distributed Optimal Control of Two-Wheeled Unmanned Vehicles</p>
        <p>
          Development and application of mean-field differential game theory for distributed,
          non-cooperative optimal control of partially observed large-scale two-wheeled unmanned vehicles.
        </p>
        <div class="rf-placeholder">Image Placeholder: two-wheeled vehicle control results</div>
      </div>

      <div class="rf-block">
        <p class="rf-subtitle">Distributed Optimal Control of Hexarotor (Stackelberg Game)</p>
        <p>
          Application of partially observed mean-field Stackelberg game theory for leader-follower
          distributed optimal flight control of large-scale hexarotor groups.
        </p>
        <div class="rf-placeholder">Image Placeholder: hexarotor formation and trajectory results</div>
      </div>
    </div>
  </section>

  <section class="rf-section">
    <h2 class="rf-title">Reinforcement Learning and Machine Learning Theory and Applications</h2>
    <div class="rf-body">
      <p class="rf-subtitle">Core Topics</p>
      <ul>
        <li>RL-based UAV path planning and collision avoidance algorithms</li>
        <li>RL-based active management for power systems and emergency load shedding</li>
        <li>Single-policy multi-objective reinforcement learning for Pareto front expansion</li>
      </ul>

      <div class="rf-block">
        <p>
          Theory and implementation of reinforcement learning and machine learning methods for
          robust control, energy systems, and autonomous decision-making under uncertainty.
        </p>
        <div class="rf-placeholder">Image Placeholder: RL architecture, optimization, and simulation outputs</div>
      </div>
    </div>
  </section>

  <section class="rf-section">
    <h2 class="rf-title">Autonomous Driving and Intelligent Robot Control</h2>
    <div class="rf-body">
      <p class="rf-subtitle">Core Topics</p>
      <ul>
        <li>Intelligent control algorithms for multi-platform mobile robots</li>
        <li>Autonomous driving algorithm development and validation for ERP-42 vehicle</li>
        <li>Simulation-to-real evaluation using MORAI and real-world test environments</li>
      </ul>

      <div class="rf-block">
        <p>
          Research and implementation of intelligent robot and autonomous driving control methods
          across practical platforms including mobile robots, manipulators, and autonomous vehicles.
        </p>
        <div class="rf-placeholder">Image Placeholder: robot platforms, K-city test, and MORAI simulation</div>
      </div>
    </div>
  </section>
</div>
