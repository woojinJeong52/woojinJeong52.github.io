---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
_styles: >
  .pub-subnav {
    display: flex;
    flex-wrap: wrap;
    gap: 1.8rem;
    margin: 0.5rem 0 1.2rem 0;
    padding-bottom: 0.8rem;
    border-bottom: 2px solid var(--global-divider-color);
  }
  .pub-subnav a {
    font-size: 1.15rem;
    font-weight: 600;
    text-decoration: none;
  }
  .pub-section {
    margin-top: 2.5rem;
  }
  .pub-section h2 {
    text-align: center;
    font-size: 2.4rem;
    margin-bottom: 1.4rem;
  }
  .pub-section hr {
    margin: 0.8rem 0 1.4rem 0;
  }
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<nav class="pub-subnav">
  <a href="#international-journals">International Journals</a>
  <a href="#international-conferences">International Conferences</a>
  <a href="#domestic-journals">Domestic Journals</a>
  <a href="#domestic-conferences">Domestic Conferences</a>
</nav>

<div class="publications">
  <section id="international-journals" class="pub-section">
    <h2>International Journals</h2>
    <hr>
    {% bibliography %}
  </section>

  <section id="international-conferences" class="pub-section">
    <h2>International Conferences</h2>
    <hr>
    {% bibliography %}
  </section>

  <section id="domestic-journals" class="pub-section">
    <h2>Domestic Journals</h2>
    <hr>
    {% bibliography %}
  </section>

  <section id="domestic-conferences" class="pub-section">
    <h2>Domestic Conferences</h2>
    <hr>
    {% bibliography %}
  </section>

</div>
