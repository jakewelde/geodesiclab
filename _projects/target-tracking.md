---
title: 'Autonomous Target Tracking'
subtitle: 'Tracking moving objects using only onboard sensing, perception, and computation.'
date: 2017-05-08 00:00:00
description: 
featured_image: '/images/projects/tracking.png'
publications:
  - key: Thomas2017
people: 'Justin Thomas, Jake Welde, Giuseppe Loianno, Kostas Daniilidis, and Vijay Kumar'
---

<!-- 2017  -->

![Stroboscopic Photograph of Moving Target Tracking](/images/projects/tracking.png)

*The aerial vehicle detects the moving target using its downward camera. It reacts, keeping the target in the field of view while converging to match the target's motion.*

In this work, we enable a small quadrotor to autonomously track a moving target and plan trajectories that allow the robot to converge on the target. Our approach respects the dynamic, sensor, and actuator constraints of the vehicle, in particular ensuring that the target does not leave the field of view of the camera, which is rigidly attached to the robot and therefore affected by the coupled dynamics of the system. One of the major contributions of this work is that all sensing and computation is done onboard the 250 g vehicle, with no outside assistance from motion capture systems or external processors.

<iframe width="420" height="315" src="https://www.youtube.com/embed/LDE1jyyQUWc" frameborder="0" allowfullscreen></iframe><br/>
