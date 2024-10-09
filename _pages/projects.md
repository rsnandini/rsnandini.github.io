---
layout: page
title: Projects
permalink: /projects/
# description: <h6>We aim to address <b>sustainability, reliability, and efficiency</b> of machine learning, by selecting the most relevant data for training, among other techniques.</h6>
nav: true
nav_order: 3
display_categories: [Ph.D., Project, Master's, Internship]
horizontal: false
---
<!-- We aim to address <span class="emp"><b>sustainability, reliability, and efficiency</b></span> of machine learning, by selecting the most relevant data for training, among other techniques. -->




<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  {%- if category == 'Ph.D.' %}
    <a id="Ph.D."></a>
  {%- endif -%}
  {%- if category == 'Project' %}
    <a id="Project"></a>
  {%- endif -%}
  {%- if category == 'Master's' %}
    <a id="Master's"></a>
  {%- endif -%}
  {%- if category == 'Internship' %}
    <a id="Internship"></a>
  {%- endif -%}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
