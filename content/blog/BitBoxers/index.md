+++
title = 'BitBoxers'
date = 2022-05-22T09:03:08+08:00
draft = false
categories = ['Game Design' , 'Game Programming']
tags = ['Combat Design', 'C', 'Embedded Software']
series = 'headline'
+++

For my computer engineering capstone project, I worked with a team to create an arcade fighting game, but with a major twist - the combat was turn based.

<!--more-->

## Project Overview

{{<youtube G9133s1H3og>}}

In this project, we had the idea to utilize the wireless communication features of the microcontrollers we were working with to create a simple game that two players could use to play with each other using on handheld 'consoles'. I obviously wanted to make a fighting game (I love fighting games) but we had a major hardware limitation in the fact that there was significant latency between either device. I ended up moving towards a design where either player could act asynchronously, drawing inspiration from auto-battler games like Super Auto Pets. Once a player had selected their sequence of attacks, they would then communicate commands to each other and have the fight play out.

{{<figure src="bitboxersgif1.gif" >}}

Of course, I still wanted to make it as "fighting game-y" as possible. I designed a boxing-themed combat system with several different types of attacks. In the absence of movement, I still wanted to reward reads and conditioning, so I had successful dodges restore stamina, creating a risk-reward paradigm in choosing to use a specific dodge as opposed to blocking. I brought this same paradigm to the various attacks, having some deal low damage but act as countermeasures to dodges, whereas others would damage yourself if dodged or blocked but take a huge chunk from the opponent's stamina bar. With this system, I felt that I was able to achieve a similar feeling of strategic depth, even in the absence of mechanical considerations like frame data and whiff punishing.

{{<figure src="bitboxers1.png" title="Move interaction rules">}}


## Responsibilities
- I designed the core game loop of an asynchronous PVP fighting game, working within the hardware limitations while maintaining the original vision of a combat system with strategic depth
- I balanced the various moves included in the game, adjusting their interactions with other move, damage values, and costs
- I programmed the core game loop using C, collecting player input from the connected buttons and translating them to discrete game states
- I programmed the graphics drivers to display the game visuals on an LCD screen, as well as a compression algorithm to reduce the file size of the sprites displayed.


## Skills
<mark>Game Design - PVP Combat</mark>

<mark>Game Design - Asynchronous Multiplayer</mark>

<mark>Embedded Software</mark>


