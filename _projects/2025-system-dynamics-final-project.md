---
layout: project
title: System Dynamics - Sailboat Simulation
description: Final project modeling and autonomous sailboat
technologies: [MATLAB]
image: /assets/Sailboat Simulation.pdf
---

The final group assignment for MAE 3260 - System Dynamics asked to model a system of interest using skills and concepts from the class. Our chosen system, an autonoumous sailboat, is set to travel a fixed trajectory and speed while encountering disturbance in its route. Using our knowledge of controls, we can model a system that realistically, is very complex given its own physical limitations and environmental factors. Our simplified model allows us to define a PD controller and create MATLAB scripts to visualize our developed state space model for implementing line-following sailing conditions. 

For this assignment I used our state space and PD controller models to write a MATLAB script showing the sailboat's heading angle over time compared to a reference angle to show the effectiveness of our PD controller affecting the rudder angle that ultimatly drives our boat. 

[PDF of code and plot]({{ "/assets/sailboat_simulation.pdf" | relative_url }})


