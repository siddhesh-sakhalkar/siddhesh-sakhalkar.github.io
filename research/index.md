---
title: Research
nav:
  order: 2
  tooltip: Projects, Areas of Interest
---

# {% include icon.html icon="fa-solid fa-wrench" %}**Research**

Our research interests fall in the following categories: (1) Scientific Machine Learning for Engineering Simulations, (2) Structural Mechanics and Dynamics, with a focus on System Identification, Design Optimization and Uncertainty Quantification, (3) Fluid Mechanics and Fluid-Structure Interactions, particularly at the micro- and nanoscale. More information is given below by category. 

{% include section.html %}

## **(1) Scientific Machine Learning (SciML) for Engineering Simulations**

Designing complex engineering systems requires the formulation of non-linear, coupled, multi-physics models governed by partial differential equations (PDEs). Traditionally, these PDEs are solved using numerical methods such as Finite Difference, Finite Element and Finite Volume. However, the high computational cost associated with these methods — particularly in the context of repeated PDE evaluations required for design optimization — poses a major bottleneck to rapid and efficient design iterations. 

To address this challenge, we build new SciML models using state-of-the-art frameworks, including neural operators and foundation models, to create robust, accurate and efficient surrogate models for PDE-governed systems. These surrogate models enable rapid approximation of the PDE solution operator, dramatically reducing the computational burden of repeated PDE solves. Our research addresses complex, multiscale and multi-physics problems across solid mechanics, fluid mechanics, tribology and heat transfer. In particular, we emphasize the development of SciML methods with direct applicability to real-world engineering design problems, including large-scale, three-dimensional systems with complex geometries and features. 

{%
  include figure.html
  image="images/SciML.png"
  width="800px"
%}

{% include section.html %}

## **(2) Structural Mechanics and Dynamics: System Identification, Design Optimization, Uncertainty Quantification**

At the M<sup>3</sup> lab, we develop physics-based and data-driven models to predict the structural mechanics and dynamics of electro-mechanical devices such as hard disk drives, micro-electro-mechanical systems (MEMS) and other hardware platforms. We use these models to support downstream tasks of industry relevance such as design and topology optimization, sensitivity analysis, system identification, inverse problems and uncertainty quantification. 

Our research focuses on developing probabilistic simulation methods to quantify variability in the static and dynamic response of engineering structures caused by uncertainty in material properties, geometry or loading. We also develop scalable deep learning frameworks for robust estimation and classification of modal parameters from large-scale, experimentally acquired frequency response function (FRF) datasets. Collectively, our research helps predict and improve both the nominal structural response and device-to-device response variation of electromechanical devices.

{%
  include figure.html
  image="images/Structural_Dynamics.png"
  width="1000px"
%}

{% include section.html %}

## **(3) Micro- and Nanoscale Fluid Mechanics and Fluid-Structure Interactions**

Our research focuses on understanding the fundamental physics of fluid flows and fluid-structure interactions at the micro and nano scale, which occur in diverse applications such as microfluidic devices, tribological systems, biological systems and micro-electro-mechanical systems (MEMS). Modeling mechanical systems at these length scales presents unique challenges due to size-dependent properties and physical behaviors not seen in macroscale systems. 

In particular, to accurately model micro- and nanoscale fluid flows, effects such as surface tension, slip boundary conditions, film thickness dependent viscosity, intermolecular forces, and surface roughness may need to be considered. Moreover, the working fluids in such systems commonly exhibit non-Newtonian characteristics (e.g., viscoelasticity, shear-rate dependent viscosity) that can significantly alter flow dynamics and fluid-structure coupling. At the M<sup>3</sup> lab, we develop advanced analytical and computational methods to resolve these complex flow fields and help build predictive frameworks for micro- and nanoscale engineering applications.

{%
  include figure.html
  image="images/Fluid_Mechanics.png"
  width="1000px"
%}

{% include section.html %}
