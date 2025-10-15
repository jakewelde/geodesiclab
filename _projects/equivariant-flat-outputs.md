---
title: 'Flatness and Symmetry'
subtitle: 'Uncovering connections between symmetry and differential flatness in mechanical systems.'
date: 2023-05-29 00:00:00
description: 
featured_image: '/images/projects/flat_systems.svg'
publications:
  - key: Welde2023
  - key: welde2023automatic
people: 'Jake Welde, Matthew D. Kvalheim, and Vijay Kumar'
---

<!-- 2023 -->


![Flat Systems]({{ '/images/projects/flat_systems.svg' | relative_url }})

*The paper below includes a partial catalog of mechanical systems with geometric flat outputs, including worked examples the planar rocket, the planar aerial manipulator, and the quadrotor (shown above).*

Mechanical systems naturally evolve on principal bundles describing their inherent symmetries. The ensuing factorization of the configuration manifold into a symmetry group and an internal shape space has provided deep insights into the locomotion of many robotic and biological systems. On the other hand, the property of differential flatness has enabled efficient, effective planning and control algorithms for various robotic systems. Yet, a practical means of finding a flat output for an arbitrary robotic system remains an open question. In this work, we demonstrate surprising new connections between these two domains, for the first time employing symmetry directly to construct a flat output. We provide sufficient conditions for the existence of a trivialization of the bundle in which the group variables themselves are a flat output. We call this a geometric flat output, since it is equivariant (i.e. maintains the symmetry) and is often global or almost-global, properties not typically enjoyed by other flat outputs. In such a trivialization, the motion planning problem is easily solved, since a given trajectory for the group variables will fully determine the trajectory for the shape variables that exactly achieves this motion. We provide a partial catalog of robotic systems with geometric flat outputs and worked examples for the planar rocket, planar aerial manipulator, and quadrotor.

<iframe width="420" height="315" src="https://www.youtube.com/embed/oMvF86MXTyY" frameborder="0" allowfullscreen></iframe><br/>
