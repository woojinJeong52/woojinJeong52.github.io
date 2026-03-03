---
layout: page
permalink: /professor/
title: Professor
description: professor of the lab
nav: false
nav_order: 6
_styles: >
  .professor-card {
    display: flex;
    align-items: flex-start;
    gap: 2rem;
    margin: 1rem 0 2rem 0;
    padding: 1rem;
    border: 1px solid var(--global-divider-color);
    background: rgba(255, 255, 255, 0.03);
  }
  .professor-card img {
    width: 300px;
    height: auto;
    border-radius: 6px;
  }
  .professor-card__info {
    text-align: left;
    font-size: 1.15rem;
    line-height: 1.35;
  }
  .professor-card__info p {
    margin: 0 0 0.28rem 0;
  }
  .professor-section {
    margin-top: 2rem;
  }
  .professor-section h2 {
    margin-bottom: 0.6rem;
    padding-bottom: 0.2rem;
    border-bottom: 1px solid var(--global-divider-color);
    color: #5a84c2;
    font-size: 2rem;
    font-weight: 700;
  }
  .professor-section ul {
    margin: 0.3rem 0 0 1.4rem;
    padding: 0;
  }
  .professor-section li {
    margin-bottom: 0.45rem;
    line-height: 1.45;
    font-size: 1.04rem;
  }
  @media (max-width: 900px) {
    .professor-card {
      flex-direction: column;
    }
    .professor-card img {
      width: min(100%, 340px);
    }
  }
---

<div class="professor-card">
  <img src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Myoung Hoon Lee">
  <div class="professor-card__info">
    <p><strong>Myoung Hoon Lee</strong></p>
    <p><strong>Assistant Professor</strong></p>
    <p>College of Engineering</p>
    <p>Department of Electrical Engineering</p>
    <p>Incheon National University, Incheon, South Korea</p>
    <p>Address: Room 251, Building 8-B, Incheon National University,</p>
    <p>119 Academy-ro, Yeonsu-gu,</p>
    <p>Incheon, South Korea</p>
    <p>Contact: mh.lee@inu.ac.kr</p>
  </div>
</div>

<section class="professor-section">
  <h2>Education</h2>
  <ul>
    <li>Ph.D. (Feb. 2021), Electrical Engineering, Ulsan National Institute of Science and Technology (UNIST), Ulsan, South Korea</li>
    <li>B.S. (Feb. 2016), Kyungpook National University, Daegu, South Korea</li>
  </ul>
</section>

<section class="professor-section">
  <h2>Working Experience</h2>
  <ul>
    <li>Assistant Professor (Mar. 2023 – Present), Department of Electrical Engineering, Incheon National University, Incheon, South Korea</li>
  </ul>
</section>

<section class="professor-section">
  <h2>Research Interests</h2>
  <ul>
    <li>Deep Reinforcement Learning</li>
    <li>Intelligent Control Theory</li>
    <li>Power System Optimization and Topology Control</li>
    <li>Smart Grid and Active Network Management</li>
    <li>UAV Control and Autonomous Systems</li>
    <li>Power Electronics Applications</li>
  </ul>
</section>

<section class="professor-section">
  <h2>Selected Journal Publications</h2>
  <ul>
    <li>Option-Based Deep Reinforcement Learning for Topology Control of Power Systems, IEEE Access, Vol. 13, pp. 26639-26650, Feb. 2025</li>
    <li>Optimal MOSFET Selection Method for DAB-Based Fast EV Chargers Using Deep Learning, Journal of Power Electronics, Vol. 29, No. 6, pp. 493-502, Dec. 2024</li>
    <li>Koopman-Based Control System for Quadrotors in Noisy Environments, IEEE Access, Vol. 12, pp. 71675-71684, May 2024</li>
    <li>Deep Reinforcement Learning-Based Active Network Management and Emergency Load-Shedding Control for Power Systems, IEEE Transactions on Smart Grid, Vol. 15, No. 2, pp. 1423-1437, Mar. 2024</li>
    <li>Deep Reinforcement Learning-Based Model-Free Path Planning and Collision Avoidance for UAVs: A Soft Actor-Critic with Hindsight Experience Replay Approach, ICT Express, Vol. 9, No. 3, Jun. 2023</li>
  </ul>
</section>
