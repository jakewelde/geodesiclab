---
title: 'Weak Symmetry in Control Systems'
subtitle: 'A relaxed notion of group invariance that balances structure with generality.'
date: 2026-06-08 00:00:00
description: 
featured_image: '/images/projects/weak_invariance.svg'
publications:
  - key: welde2026weaknotionsymmetrydynamical
  - key: link2026reductionworkshop
people: 'Jake Welde, Pieter van Goor, and Riley Link'
---

![Commutative Diagram for Weak Invariance of a discrete-time control system.]({{ '/images/projects/weak_invariance.svg' | relative_url }})

*Weak invariance generalizes the classical notion of group invariance (the special case in which $$\sigma : G \to G$$ is the identity map).*


Symmetry has long played a role in enabling high-dimensional robotic systems to operate autonomously in complex environments and under previously unseen conditions, despite stringent computational constraints. Nonetheless, the classical notion of symmetry is too rigid to be applied to many real-world robotic systems, where symmetry may be “broken” by external forces or confined to only a portion of the overall system. To overcome these limitations, we propose a relaxed notion of symmetry — termed “weak invariance” — that balances structure with generality. In recent work, we show that weak invariance is in fact a necessary and sufficient condition for the reduction of control problems pertaining to relative motion. Ultimately, these reductions can be leveraged for sample-efficient learning of tracking controllers for robotic systems.

![Group Action on Quadrotor.]({{ '/images/projects/quadrotor_transformation.png' | relative_url }})

*The usual action of $\mathrm{SE}(3)$ on an aerial vehicle is not a classical ("strong") symmetry (since it is broken by gravity). However, the system nonetheless enjoys a nine-dimensional weak symmetry described in terms of the extended pose group $\mathrm{SE}_2(3)$, which can be factored out of the joint dynamics governing the tracking control problem.*