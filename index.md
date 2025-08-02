---
---

# CRII: III: Explainable Multi-Source Data Integration with Uncertainty

Sensors are all around us collecting data. Each sensor may provide complementary or reinforced information that supports tasks such as target detection, classification, or scene understanding. In remote sensing applications, for example, hyperspectral imaging sensors can provide spectral information about materials by using a wide range of wavelengths, while LiDAR (light detection and ranging) measures an object's elevation above the ground. If a road and a building rooftop are built with the same material (e.g., asphalt), hyperspectral information alone may not be sufficient to tell them apart, while integrating height information from LiDAR data makes it easier to distinguish the two. 

This project develops innovative mathematical framework and associated algorithms for integrating such sensor data from multiple sources. Multiple works stem from this project, ranging from several novel multiple instance Choquet integral fusion approaches, cross-modality (thermal and RGB) fusion networks for pedestrian detection, a domain adaptive object detection method, and an efficient scene segmentation method for unstructured terrain. Applications of these approaches includes autonomous vehicles and mobile robotic systems and multi-modal and multi-sensor fusion (RGB, LiDAR, Hyperspectral, Thermal, and SONAR). We also explore enhanced explainability in multi-source data integration.

{% include section.html %}

## Highlights

{% capture text %}


{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}


{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}


{%
  include button.html
  link="news"
  text="See News Archive"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="News"
  text=text
%}
