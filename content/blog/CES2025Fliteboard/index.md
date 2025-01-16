+++
title = 'Brunswick - CES 2025 Fliteboard Simulator'
date = 2025-01-07T09:03:09+08:00
draft = false
categories = 'Game Programming'
tags = ['Unreal Engine', 'Computer Vision', 'C++', 'Blueprint Scripting', 'Python', 'C#']
series = 'headline'
+++


In my internship and co-op at Brunwick's BI (Boating Intelligence) Design Lab, I worked with subsidiary company Fliteboard to create an interactive immersive hydrofoiling experience for Consumer Electronics Show 2025.

<!--more-->

## Project Overview

Near the end of my summer internship at Brunswick's BI Design Lab, I was assigned a new project, to create a proof-of-concept for a hydrofoil simulator to market one of the company's new products, the Fliteboard. Working with one other intern, we created a pose estimation system that would control an Unreal Engine game, similarly to the Xbox kinect. In the fall, I continued my internship as a full-time co-op with Brunswick, where I spent a lot of time polishing up this experience to be used at CES.


As effectively the sole developer for the majority of this project, I had the opportunity to explore both the engineering challenge of developing an experience like this as well as the design challenge of accommodating a flow of people for a bite-sized live experience. I also had the opportuniy to travel to CES, where this project was the standout highlight of the Brunswick booth, with thousands of people trying and loving it.


{{youtubetime f6EfMkiondU 765}}


https://www.thefoilingmagazine.com/just-in/fliteboard-simulator-at-ces-2025/


On the engineering side, I was able to gain a vast breadth of experience by developing this project from start to end, including fine-tuning a pose estimation model, integrating reactive sound, developing unique post-process effects, procedural generation, and interfacing with proprietary hardware. I was also able to leverage some of my work from earlier in the summer, such as the TCP websockets plugin developed for the FutureHelm project.


From a design perspective, I essentially had free reign given the basic requirements of the project. The decisions I made had a very subtle impact in terms of complexity, but I personally believe they greatly improved the functionality, robustness, and immersiveness of the experience. For example, I structured the interpretation of the pose estimation's output angles to work well regardless of the player's stance. Coupled with the lack of a 'lose' state, it greatly streamlined the flow of attendees by making the control of the simulator far more intuitive. I also designed other QoL features such as easy timer controls and reset mechanisms that would make facilitating the experience much easier for exhibitors. Some features also were designed for the sake of improving immersiveness, such as a custom radial motion blur at the edges of the screen to give the illusion of speed, and varying engine/wind/water audio volumes based on the player's speed.

## Responsibilities

- Designed and programmed physics and game loop for a first-person eFoil simulator using Blueprints and C++.
- Fine-tuned and deployed TensorFlow-based pose estimation model and developed algorithm to derive an stance-agnostic center of gravity and lean angle to control simulator.
- Modified websockets communication plugin and server system to accept inputs relayed from pose estimation model and bluetooth-based physical controller.
- Designed level layout with randomized/procedural elements and game flow for 45-second experience.
- Created immersive sound design sequences to be reactive to player input and environment.
- Designed and programmed unique post-process materials to enhance visuals.
- Modified designed and features based on feedback from Fliteboard team.
- Showcased simulator at CES 2025.

## Skills
<mark>Unreal Engine 5</mark> 

<mark>C++ plugin development</mark> 

<mark>Python</mark> 

<mark>Computer Vision</mark> 

<mark>UX Design</mark>

<mark>Game Design</mark>

<mark>Perforce</mark> 


