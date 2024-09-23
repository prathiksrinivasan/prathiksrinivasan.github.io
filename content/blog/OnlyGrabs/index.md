+++
title = 'OnlyGrabs'
date = 2021-12-01T09:03:08+08:00
draft = false
categories = ['Game Design' , 'Game Programming']
tags = ['Combat Design', 'Unity', 'C#']
series = 'headline'
+++

For my Game Prototyping course's final project, I designed and developed a combat system for a fighting game where grabs are the only form of attacking. 

<!--more-->

## Project Overview

{{< youtube PmFPMAdWyBk >}}

[Project Link](https://spooncats.itch.io/onlygrabs)

My initial idea was for a fighting game focused specifically around grabs, without strikes of any type. To minimize the amount of technical work and focus mostly on design, I made use of a fighting game framework for Unity. This was my first exploration with fighting game design and combat design in general, so I wanted to primarily focus on polishing that aspect.

In traditional fighting games, throws complete the rock-paper-scissors system, defeating an opponent's blocking defense against strikes. In the absence of strikes, there was no need for blocking either, so I instead devised a system that would revolve around grabs and dodges. Players would move back and forth to bait and punish grab attempts with dodging and rolling existing as additional movement mixups.

{{< figure src="onlygrabs2.png" title="Editing move frame data with a hitbox/hurtbox editor">}}

I designed the hitboxes, hurtboxes, and frame data for each move, and kept track of their values in a CSV data table to allow me to more easily observe and change the numbers.

{{< figure src="onlygrabs3.png" title="Data table for frame data">}}


## Reflection
My biggest takeaway overall from this prototype is how various elements of a character's moveset come together to create an overall play style. In the case of a grappler, much of the focus of their moveset are the grabs itself, and many would say that a big part of these characters' appeal is landing one big grab to do a lot of damage. However, part of what enables that grab game is the existence of striking and blocking. It's not the grab itself that appeals to people, but rather the ability to condition their opponent to be afraid of a certain attack, and then reading their reactions to make them take huge punishing attacks. That read-based gameplay was something that was missing from the overall vibe of this design, and is something I would like to fix if I returned to this concept.


## Skills
<mark>Unity</mark> 

<mark>Combat Design - Core Player Moveset</mark>

<mark>Combat Design - Enemy AI</mark>

<mark>Combat Design - Balancing</mark>



