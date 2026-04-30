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
  - name: "Unity"
    icon: "fa-brands fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Developing prototypes alone and in a group"
    years: 1
  - name: "Video Creation"
    icon: "fa-solid fa-video"
    badges: ["Filming", "Photography", "Editing", "Scoring"]
    text: "Creating and editing videos of both real life and video games."
    years: 4
  
---

{% include skills skills=page.skills %}

{% include google-form
  title="Contact Me"
  src="https://forms.gle/xLp6m2uHt8w4MRsS7"
  height="800"
%}
