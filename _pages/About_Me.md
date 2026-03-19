---
title: "About-Me"
layout: default
permalink: /about-me/

skills:
  - name: "Unreal Engine 5"
    icon: "fa-brands fa-unreal-engine"
    badges: ["C++", "Game Dev"]
    text: "Created a few game prototypes and a functional game"
    years: 2
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Designed mechanics, levels, and player feedback loops."
    level_label: "Beginner"
  
---

{% include skills skills=page.skills %}

{% include figure image_path="assets/images/WIP.jpg" alt="WIP IMAGE" caption="Work in Progress" %}

{% include google-form
  title="Contact Me"
  src="https://forms.gle/XsbApFoRjn7r24jy6"
  height="800"
%}
