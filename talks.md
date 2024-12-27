---
layout: page
title: Talks
---

## Conference & Invited Talks

### NeurIPS 2024 ML4CFD Competition
*Vancouver, Canada - December 14, 2024*  
**Invited Talk**

**Title:** Harnessing Machine Learning for Computational Fluid Dynamics in Airfoil Design  
**Abstract:** We present MARIO (Multiscale Aerodynamic Resolution Invariant Operator), a conditional neural field approach tailored for aerodynamic predictions. MARIO employs multiple input Fourier feature embeddings at different scales to optimize the reconstruction accuracy across the different frequency components, especially for multi-output predictions. The architecture is conditioned through a hypernetwork and FiLM modulation on the free-stream conditions and airfoil geometry, parameterized through thickness and camber distributions. We enhance the traditional coordinate and signed distance function inputs with a continuous normal vector field on and off the airfoil surface aiming to provide a translation invariant frame of reference, augmenting the implicit distance information...

[View Slides](assets/files/ML4CFDNips24_talk.pdf)

### ELLIS Machine Learning Insights Seminar
*TU Delft, Delft, Netherlands - November 26, 2024*  
**Invited Talk**

**Title:** Neural Fields for Physics Simulation  
**Abstract:** Recent advancements in deep learning offer powerful tools for accelerating simulations of complex systems governed by Partial Differential Equations (PDEs), particularly in computational fluid dynamics (CFD), structural mechanics, and climate modeling. Traditional numerical solvers, while highly accurate, can be computationally expensive for preliminary analysis or optimization where an extensive exploration of the design space is performed. On the other hand, Neural Fields offer a powerful framework for Operator Learning by parameterizing continuous functions over the physical space using neural networks, enabling discretization-invariant representations of arbitrary functions...

[View Slides](assets/files/ELLIS_talk.pdf)

### Machine Learning For Fluid Dynamics Workshop
*Sorbonne University, Paris, France - March 6-8, 2024*  
**Conference Talk**

**Title:** Spatial Implicit Neural Representation for the transonic aerodynamics over an airfoil  
**Abstract:** This workshop paper aims to demonstrate the potential of Spatial Implicit Neural Representations (INRs) as surrogate models for the prediction of the highly nonlinear compressible aerodynamics over the RAE2822 airfoil, while comparing its performance to emerging data-driven methods such as Graph Neural Networks (GNN) and well established surrogates based on Proper Orthogonal Decomposition (POD). A validated dataset of more than 2.000 RANS simulations at various angles of attack and Mach numbers is used to train fast and accurate surrogate models of the pressure field. Following to the recently proposed CORAL and INFINITY our study simplifies the scenario to a fixed geometry, steady case, and a wide variation in the flight conditions up to the transonic regime. This specific choice also allows us to draw clear comparisons with traditional methods such as POD in a controlled setting...

[View Slides](assets/files/ERCOFTACTMLFluid_talk.pdf)