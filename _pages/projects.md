---
layout: page
title: projects
permalink: /projects/
description: A growing collection of your cool projects.
nav: true
nav_order: 3
---

<!-- pages/projects.md -->

# Projects

---

## 🛰️ Artificial Intelligence based Remote Sensing

{% assign ai_projects = site.projects | where: "category", "Artificial Intelligence based Remote Sensing" %}
<div class="row row-cols-1 row-cols-md-3">
  {% for project in ai_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

---

## 💧 Gorgovivo 4.0: Intelligent Monitoring and Optimization of Groundwater for the Ancona Province

{% assign groundwater_projects = site.projects | where: "category", "Gorgovivo 4.0: Intelligent Monitoring and Optimization of Groundwater for the Ancona Province" %}
<div class="row row-cols-1 row-cols-md-3">
  {% for project in groundwater_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

---

## 📊 Intelligent Text Mining Approaches for Technology Forecasting

{% assign textmining_projects = site.projects | where: "category", "Intelligent Text Mining Approaches for Technology Forecasting" %}
<div class="row row-cols-1 row-cols-md-3">
  {% for project in textmining_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

---

## 🌍 Policy, Strategy and Organization Analysis for Sustainability

{% assign policy_projects = site.projects | where: "category", "Policy, Strategy and Organization Analysis for Sustainability" %}
<div class="row row-cols-1 row-cols-md-3">
  {% for project in policy_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>
