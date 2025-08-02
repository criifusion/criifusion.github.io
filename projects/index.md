---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

This CRII project investigates weakly supervised machine learning and multi-source data integration. Through this project, several machine learning and deep learning algorithms were developed to learn from and integrate multi-source and multi-modal sensor data. The developed algorithms were capable of learning the relationships and non-linear interactions among multiple sources during data integration, while addressing data and label uncertainties commonly observed in real-world sensor data. 

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Software

{% include list.html component="card" data="projects" filter="!group" style="small" %}
