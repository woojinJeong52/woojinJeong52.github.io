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
  .pub-subnav .pub-tab {
    background: transparent;
    border: 0;
    padding: 0;
    cursor: pointer;
    color: var(--global-theme-color);
    font-size: 1.15rem;
    font-weight: 600;
    text-decoration: none;
  }
  .pub-subnav .pub-tab.active {
    color: var(--global-text-color);
  }
  .pub-subnav .pub-tab:hover {
    text-decoration: underline;
  }
  .pub-section {
    margin-top: 2.5rem;
  }
  .pub-section.hidden {
    display: none;
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
  <button type="button" class="pub-tab active" data-target="international-journals">International Journals</button>
  <button type="button" class="pub-tab" data-target="international-conferences">International Conferences</button>
  <button type="button" class="pub-tab" data-target="domestic-journals">Domestic Journals</button>
  <button type="button" class="pub-tab" data-target="domestic-conferences">Domestic Conferences</button>
</nav>

<div class="publications">
  <section id="international-journals" class="pub-section">
    <h2>International Journals</h2>
    <hr>
    {% bibliography %}
  </section>

  <section id="international-conferences" class="pub-section hidden">
    <h2>International Conferences</h2>
    <hr>
    {% bibliography %}
  </section>

  <section id="domestic-journals" class="pub-section hidden">
    <h2>Domestic Journals</h2>
    <hr>
    {% bibliography %}
  </section>

  <section id="domestic-conferences" class="pub-section hidden">
    <h2>Domestic Conferences</h2>
    <hr>
    {% bibliography %}
  </section>

</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const tabs = document.querySelectorAll(".pub-tab");
    const sections = document.querySelectorAll(".pub-section");

    tabs.forEach((tab) => {
      tab.addEventListener("click", function () {
        const targetId = this.dataset.target;

        tabs.forEach((t) => t.classList.remove("active"));
        this.classList.add("active");

        sections.forEach((section) => {
          section.classList.toggle("hidden", section.id !== targetId);
        });
      });
    });
  });
</script>
