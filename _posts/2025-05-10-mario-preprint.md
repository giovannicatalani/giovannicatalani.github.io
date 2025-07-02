---
layout: post
title:  "New Preprint Available: Towards scalable surrogate models based on Neural Fields for large scale aerodynamic simulations"
date:   2025-05-10
tags:   [update]
---

### Towards scalable surrogate models based on Neural Fields for large scale aerodynamic simulations (2025)
*Arxiv Preprint, Under Review*

![MARIO paper cover](/assets/img/new_overview_final.png){: width="700px" }


**Abstract:** This paper introduces a novel surrogate modeling framework for aerodynamic applications based on Neural Fields. The proposed approach, MARIO (Modulated Aerodynamic Resolution Invariant Operator), addresses non parametric geometric variability through an efficient shape encoding mechanism and exploits the discretization-invariant nature of Neural Fields. It enables training on significantly downsampled meshes, while maintaining consistent accuracy during full-resolution inference. These properties allow for efficient modeling of diverse flow conditions, while reducing computational cost and memory requirements compared to traditional CFD solvers and existing surrogate methods. The framework is validated on two complementary datasets that reflect industrial constraints. First, the AirfRANS dataset consists in a two-dimensional airfoil benchmark with non-parametric shape variations. Performance evaluation of MARIO on this case demonstrates an order of magnitude improvement in prediction accuracy over existing methods across velocity, pressure, and turbulent viscosity fields, while accurately capturing boundary layer phenomena and aerodynamic coefficients. Second, the NASA Common Research Model features three-dimensional pressure distributions on a full aircraft surface mesh, with parametric control surface deflections. 

[Paper PDF](https://arxiv.org/abs/2505.14704) | [Code Torch](https://github.com/giovannicatalani/MARIO) 