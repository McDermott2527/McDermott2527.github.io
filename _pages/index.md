---
title: "Portfolio Website"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/placeholder.png
  actions:
    - label: "Read CV"
      url: "assets/downloads/B01022849-  Sean.cleaned.pdf"
      target: "_blank"

excerpt: "Welcome to my portfolio website"
## Projects I've worked on
feature_row:
  - image_path: assets/images/MedScrim.png
    alt: "Medieval Scrimmage"
    title: "Medieval Scrimmage"
    excerpt: "A 2D Beat-Em-Up style group project"
  - image_path: assets/images/2DGame.png
    alt: "2D Game Project"
    title: "2D Game Project"
    excerpt: "A simple 2D platforming game"
  - image_path: assets/images/3DGame.png
    alt: "3D Game Project"
    title: "3D Game Project"
    excerpt: "A 3D platforming type game"
---

{% include button
  url="/projects/"
  label="See More Projects"
  class="btn--primary"
%}

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

