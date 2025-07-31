---
layout: page
title: Sapience Competition 2
description: Autonomous Multi-Agent Search and Rescue in GPS-Denied Environments
img: assets/img/Sapience_Alabama_Winner.jpg
importance: 1
category: work
related_publications: true
---


## From Concept to Competition: Leading a Student Project Toward Real-World Impact

Over the course of the past 1.5 years, I have led a student team at the University of Klagenfurt in an ambitious research-driven competition centered on a highly relevant topic in robotics: multi-agent autonomous systems for search and rescue operations in environments where GPS is not available. This challenge lies at the intersection of robotic autonomy, real-time perception, and collaborative decision-making—domains that are becoming increasingly critical in modern disaster response scenarios.

The core objective of our project was to design and implement an integrated system of aerial robots capable of autonomously exploring unknown environments, constructing semantic maps, and identifying actionable insights such as hazardous zones, safe access routes, or potential victims. These functionalities are intended to support first responders like the Red Cross during critical interventions in complex and potentially dangerous conditions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/sapience_comp2/side_view_drone.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/sapience_comp2/system_presentation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/sapience_comp2/flying_drones.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    TBD
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/sapience_comp2/preparation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Field tests for final integration testing, at the Hobby Airport in Klagenfurt, Austria.
</div>

### Technical Overview

Our system architecture was designed from the ground up with modularity, adaptability, and robustness in mind. It features:

<ul>
    <li>Real-time perception and semantic awareness, including object detection, dynamic tracking, and the generation of annotated maps.</li>
    <li>Multi-layered planning and execution, with both global and local path planners integrated with obstacle avoidance strategies and dynamic path adaptation.</li>
    <li>A modular autonomy stack, built around our own finite-state-machine and behavior-tree-based architecture, enabling flexible decision-making and reactivity in unstructured environments.</li>
    <li>Sensor fusion and redundancy, allowing the system to dynamically switch between multiple odometry and localization sources to ensure reliable navigation even in degraded conditions.</li>
</ul>

The entire system was deployed on board our UAVs and executed fully autonomously, with no external computation or communication infrastructure.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/sapience_comp2/me_system_pres.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/sapience_comp2/drone_me.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    TBD
</div>


### From Simulation to Real-World Demonstrations

What makes this project particularly rewarding is its real-world validation across diverse scenarios. The system was not only tested in the structured environment of competitions but also deployed in vastly different field settings, without requiring major architectural changes. Among the successful demonstrations were:

<ul>
    <li>Autonomous exploration and mapping of a highway tunnel, including obstacle avoidance and semantic annotation of detected elements.</li>
    <li>3D reconstruction of a freeway bridge, generated using onboard visual and Lidar-based mapping tools during an autonomous flight.</li>
    <li>Exploration of complex indoor buildings, with semantic detection and real-time annotation of objects of interest, simulating real-world search and rescue missions.</li>
</ul>

These tests not only demonstrated the maturity and robustness of our architecture, but also proved its adaptability to different environments and mission profiles.

### Broader Impact and Future Directions

The insights gained from this project—and the resulting software and system design—have contributed directly to our involvement in larger, high-impact initiatives such as SPRIND – Fully Autonomous Flights 2.0, funded by the German Federal Agency for Disruptive Innovation. Within this project, our research group (Control of Networked Systems) is actively contributing toward the development of fully autonomous aerial platforms for complex missions, building upon the core principles established in our earlier work.


### Reflections on Teamwork and Leadership

Beyond the technical aspects, this project has been a formative experience in leading interdisciplinary collaboration under real-world constraints. From aligning hardware-software interfaces to defining mission strategies and resolving failures in the field, the journey demanded constant adaptation, clear communication, and a shared vision within the team.

I would like to thank the brilliant students who made this possible:

<ul>
    <li>Gilbert Tanner</li>
    <li>Georg Steinthaler</li>
    <li>Tim Schumann</li>
    <li>Ben Wesse</li>
    <li>Jonas Spieler</li>
</ul>

Your dedication, creativity, and resilience shaped this project from the initial concept to a system ready for real-world deployment.


