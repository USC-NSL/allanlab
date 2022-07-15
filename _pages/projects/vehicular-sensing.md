---
title: "NSL Lab - Research"
layout: textlay
excerpt: "NSL Lab -- Research"
sitemap: false
permalink: /projects/vehicular-sensing/
---

# Vehicular Sensing

Vehicles today have several hundred sensors that are used to monitor vehicular subsystems. Such monitoring can track the health of these subsystems and can also be used to control vehicular behavior. In this project, funded by the National Science Foundation and General Motors, we explored ways in which these sensors could be used to improve vehicular safety, comfort, and performance. Many of the sensors can be accessed through a diagnostic interface using proprietary protocols, so to conduct our research, we partnered with a major car company to obtain access to these sensors.

One outcome of our research was a suite of algorithms that are used on-board sensors to improve the positioning of the vehicle. Because GPS can be inaccurate in downtown areas, we developed techniques to use onboard sensors to obtain positioning with enough accuracy to locate the vehicle within a given lane. These techniques combine GPS readings with map information, but also use vehicular sensors to determine whether a vehicle traverses a speed bump, or turns right or left, or comes to stop at a signal, then uses these determinations to learn positional corrections. These positional corrections leverage the wisdom of the crowds: if multiple cars stop at the same light, then the average of their positional readings is likely to be more accurate.

A second outcome of the research built upon this idea and developed a collection of crowd-sourcing algorithms that use onboard sensors to determine driving behavior or various aspects of the environment. Because vehicles have hundreds of sensors, if drivers would share their sensor readings (in much the same way that drivers today share information on apps like Waze), we hypothesized that we could determine various aspects of the environment such as: stop signs, road curvature, road grade, and pothole positions. We developed sensor processing and aggregation algorithms and demonstrated that these algorithms could reliably detect these environmental features.

Our most recent outcome explored a novel capability that we call Augmented Vehicular Reality (AVR). Today, and in the foreseeable future, vehicles will have “3D sensors” like LiDAR and stereo cameras. Autonomous vehicles and driver assist systems rely on these sensors. These sensors can perceive depth, but their view is limited by obstacles. AVR enables a vehicle to obtain, using wireless communication, readings from other sensors, so that the vehicle can effectively “see through” obstacles. This capability can greatly increase the safety of autonomous driving, enabling a vehicle to plan its path more effectively. The code for AVR is publicly available ([https://github.com/USC-NSL/AugmentedVehicularReality](https://github.com/USC-NSL/AugmentedVehicularReality)).

Concretely, these outcomes have resulted in two patents, several publications, and we have transitioned code to industry.

## Publications ##

<div class="publications">

{% bibliography -f papers -q @*[project=vehicular-sensing]* %}

<!-- Queries can be combined using && or || operators
-q @*[project=vehicular-sensing || project=vsensing] -->

</div>

## Patents ##

<ol>
<li>US Patent App. 15/903,616: <em>Crowd-sensed point cloud map</em>, Fawad Ahmad, Hang Qiu, Fan Bai, and Ramesh Govindan.</li>

<li>US Patent No. 17/041026: <em>Method and Apparatus of Networked Scene Rendering and Augmentation in Vehicular Environments in Autonomous Driving Systems</em>, Hang Qiu, Ramesh Govindan, Marco Gruteser, and Fan Bai.</li>
</ol>
