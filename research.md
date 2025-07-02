---
layout: page
title: Research
---

## Publications
### Geometry aware inference of steady state PDEs using Equivariant Neural Fields representations (2025)
*Arxiv Preprint, Under Review*

![enf2enf paper cover](/assets/img/enf2enf_cover-1.png){: width="700px" }


**Abstract:** Recent advances in Neural Fields have enabled powerful, discretization-invariant methods for learning neural operators that approximate solutions of Partial Differential Equations (PDEs) on general geometries. Building on these developments, we introduce enf2enf, an encoder--decoder methodology for predicting steady-state Partial Differential Equations with non-parameterized geometric variability, based on recently proposed Equivariant Neural Field architectures. In enf2enf, input geometries are encoded into latent point cloud embeddings that inherently preserve geometric grounding and capture local phenomena....... [shortened for brevity]

[Paper PDF](https://arxiv.org/abs/2504.18591) | [Code JAX](https://github.com/giovannicatalani/enf2enf) | [Code Torch](https://github.com/giovannicatalani/enf2enf_pytorch) 

### Towards scalable surrogate models based on Neural Fields for large scale aerodynamic simulations (2025)
*Arxiv Preprint, Under Review*

![MARIO paper cover](/assets/img/new_overview_final.png){: width="700px" }


**Abstract:** This paper introduces a novel surrogate modeling framework for aerodynamic applications based on Neural Fields. The proposed approach, MARIO (Modulated Aerodynamic Resolution Invariant Operator), addresses non parametric geometric variability through an efficient shape encoding mechanism and exploits the discretization-invariant nature of Neural Fields. It enables training on significantly downsampled meshes, while maintaining consistent accuracy during full-resolution inference. These properties allow for efficient modeling of diverse flow conditions, while reducing computational cost and memory requirements compared to traditional CFD solvers and existing surrogate methods. The framework is validated on two complementary datasets that reflect industrial constraints. First, the AirfRANS dataset consists in a two-dimensional airfoil benchmark with non-parametric shape variations. Performance evaluation of MARIO on this case demonstrates an order of magnitude improvement in prediction accuracy over existing methods across velocity, pressure, and turbulent viscosity fields, while accurately capturing boundary layer phenomena and aerodynamic coefficients. Second, the NASA Common Research Model features three-dimensional pressure distributions on a full aircraft surface mesh, with parametric control surface deflections. 

[Paper PDF](https://arxiv.org/abs/2505.14704) | [Code Torch](https://github.com/giovannicatalani/MARIO) 

### Neural Fields for Rapid Aircraft Aerodynamics Simulations (2024)
*Scientific Reports, Vol. 14(1), pp. 25496*

![aeronefpaper cover](/assets/img/aero_nef_cover.png){: width="700px" }


**Abstract:** This paper presents a methodology to learn surrogate models of steady state fluid dynamics simulations on meshed domains, based on Implicit Neural Representations (INRs). The proposed models can be applied directly to unstructured domains for different flow conditions, handle non-parametric 3D geometric variations, and generalize to unseen shapes at test time... [shortened for brevity]

[Paper PDF](https://www.nature.com/articles/s41598-024-76983-w) | [Code](https://gitlab.isae-supaero.fr/gi.catalani/aero-nepf) | [Data](https://gitlab.isae-supaero.fr/gi.catalani/aero-nepf)

### A Comparative Study of Learning Techniques for the Compressible Aerodynamics over a Transonic RAE2822 Airfoil (2023)
*Computers & Fluids*

![pgnet paper cover](/assets/img/pgnet_cover.png){: width="700px" }


**Abstract:** In this study, the modeling of the compressible pressure field on the RAE 2822 airfoil using deep learning (DL) is investigated. The objective is to generate, at low cost, the complete Mach envelope from a given aerodynamic database... [shortened for brevity]

[Paper PDF](https://scholar.google.com/citations?view_op=view_citation&hl=fr&user=ZO1hXHEAAAAJ&citation_for_view=ZO1hXHEAAAAJ:u-x6o8ySG0sC) | [Code](link) | [Data](https://zenodo.org/records/12700680?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjQyNzI4M2NmLWIwYjktNDc1Ny1hYjA5LTliYjU4YjY4MjFmNCIsImRhdGEiOnt9LCJyYW5kb20iOiI5ZjY5MWIzNWQ5MTRmNGE4ZDdjNmY4ZjI4MTY1NDAyMiJ9._BqW0JKCMiI89PjbTmNOtbvYO6iCBx-hjP4WRPGepV2ufmAlqk_SEmAgbPfqkW9YvjOsh67lHn2jGQ7cg_n1nw)

### Machine Learning Based Local Reduced Order Modeling for the Prediction of Unsteady Aerodynamic Loads (2022)
*Master Thesis, TU Delft*

**Abstract:** Advancements in aircraft performance require increasingly complex design processes and tools. Simulating the unsteady non-linear aerodynamic interaction between a maneuvering aircraft and the surrounding flowfield poses serious challenges... [shortened for brevity]

[Thesis PDF](https://resolver.tudelft.nl/uuid:cd5bf762-ab2a-4c9e-8b51-58a173440830) | [Code](https://github.com/giovannicatalani/CAE_ROM)