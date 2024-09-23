+++
title = 'This [blank] Does Not Exist'
date = 2023-06-29T09:03:08+08:00
draft = false
categories = ['Game Programming', 'Software Engineering']
tags = ["Unity", "C#", "JavaScript", "Google Firebase", "Data Science"]
+++

In my 2023 Summer Internship with Retora Games, I helped create a wordle-like daily puzzle game using Unity and C#.

<!--more-->

## Project Overview

As a Software Engineering Intern at a local Austin TX game studio, two other interns and I were tasked with developing a prototype for a web-based puzzle game. The goal of the game was to identify the real image when presented with a collection of 3 AI geerations and 1 actual stock photo. Though React or Flutter may have been overall more scalable for a project like this, we ultimately decided on Unity and WebGL due to the team's familiarity with the engine.

My primary responsibilities were with the UI programming and setting up telemetry. Storing player data locally is obviously very important for a game like this, as a significant appeal of the design is being able to see your own history as a player and improvements over time. On a larger scale though, we wanted to create the framework of a system that could make use of the data collectd by this web game. Much like Captcha logins, we sought to observe trends about generative AI photos, while also improving the general populace's skill in recognizing AI generations. To achieve this, I set up a Google Firebase cloud instance, calling its JavaScript API functions from Unity to remotely send results to the database.

{{< figure src="tbdne1.png" title="telemetry database design">}}

## Responsibilities
- Program UI interactions for a web-based puzzle game
- Created JavaScript library wrapper to be able to call Firebase API functions from C# scripts
- Set up Google Firebase cloud instance to store game data and observe player trends


## Skills
<mark>Unity</mark> 

<mark>C#</mark>

<mark>JavaScript</mark>

<mark>Database Design</mark>

<mark>Google Firebase</mark>


