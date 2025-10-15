---
title: 'Symmetry-Accelerated Learning'
subtitle: 'Trajectory tracking control via sample-efficient reinforcement learning.'
date: 2025-05-19 00:00:00
description: In this work, we explore the role of symmetry in accelerating reinforcement learning for trajectory tracking control in robotic systems.
featured_image: '/images/projects/astrobee.gif'
publications:
  - key: Welde2025
people: 'Jake Welde*, Nishanth Rao*, Pratik Kunapuli*, Dinesh Jayaraman, and Vijay Kumar (*equal contribution).'

---

Tracking controllers enable robotic systems to accurately follow planned reference trajectories. In particular, reinforcement learning (RL) has shown promise in the synthesis of controllers for systems with complex dynamics and modest online compute budgets. However, the poor sample efficiency of RL and the challenges of reward design make training slow and sometimes unstable, especially for high-dimensional systems. In this work, we leverage the inherent Lie group symmetries of robotic systems with a floating base to mitigate these challenges when learning tracking controllers. We model a general tracking problem as a Markov decision process (MDP) that captures the evolution of both the physical and reference states. Next, we prove that symmetry in the underlying dynamics and running costs leads to an MDP homomorphism, a mapping that allows a policy trained on a lower-dimensional "quotient" MDP to be lifted to an optimal tracking controller for the original system. We compare this symmetry-informed approach to an unstructured baseline, using Proximal Policy Optimization (PPO) to learn tracking controllers for three systems: the Particle (a forced point mass), the Astrobee (a fullyactuated space robot), and the Quadrotor (an underactuated system). Results show that a symmetry-aware approach both accelerates training and reduces tracking error at convergence.


<iframe width="560" height="315" src="https://www.youtube.com/embed/AosGBe2uzxM?si=KmxUnhFG0GfL8fmR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



<!-- A preliminary version of this work won a Best Paper Award at the [Workshop on Symmetry and Geometry in Neural Representations](https://www.neurreps.org) at NeurIPS 2024. -->
