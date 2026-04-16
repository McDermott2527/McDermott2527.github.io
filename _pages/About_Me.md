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

work-experience:
  - name: "Sales Assistant"
    badges: ["Teamwork", "Customer Service"]
    text: "Working as a cashier to check out customers and help around the store"
    employment: "Dec 2025 - Current"
  
---

{% include skills skills=page.skills %}

{% include work-experience work-experience=page.work-experience %}

{% include google-form
  title="Contact Me"
  src="https://forms.gle/XsbApFoRjn7r24jy6"
  height="800"
%}
