---
title: Publications
nav:
  order: 3
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Publications

Test change 3

{% include section.html %}

## Highlighted

{% include citation.html lookup="Predicting device-to-device frequency response function variation during high-volume manufacturing of a hardware device" style="rich" %}

{% include citation.html lookup="Effect of Rheology and Slip on Lubricant Deformation and Disk-to-Head Transfer During Heat-Assisted Magnetic Recording (HAMR)" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

<!-- <div class="accordion">
  {% assign years = site.data.citations | group_by: 'year' %}
  {% for year in years %}
    <div class="accordion-item">
      <button class="accordion-button" onclick="toggleAccordion('{{ year.name }}')">{{ year.name }}</button>
      <div id="{{ year.name }}" class="accordion-content">
        {% for citation in year.items %}
          {% include citation.html lookup=citation.title style="rich" %}
        {% endfor %}
      </div>
    </div>
  {% endfor %}
</div> -->

<div class="accordion">
  <div class="accordion-item">
    <button class="accordion-button" onclick="toggleAccordion('year-2019')">2019</button>
    <div id="year-2019" class="accordion-content">
      <!-- Publications for 2019 -->
    </div>
  </div>
</div>

{% include list.html data="citations" component="citation" style="rich" %}
