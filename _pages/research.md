---
layout: archive
title: 
permalink: /research/
author_profile: true
---

{% include base_path %}

<!---
My research interests lie in applied mathematics and scientific computing, in particular, multi-scale modeling with applications to fluid physics, materials science, and biophysics. The research goal is to establish accurate modeling of multi-scale systems relevant to meso-scale transport, non-Newtonian hydrodynamics, and kinetic transport processes arising from various science and engineering applications. For such problems, the multi-scale and high-dimensional nature imposes a fundamental challenge; empirical models based on ad-hoc closure assumptions often show limitations. Currently, my group is devoted to constructing machine-learning based models for such systems directly from the first-principle-based descriptions. In particular, we focus on developing numerical methods to learn reliable and numerically-stable models that faithfully entail the micro-scale interactions, retain physical interpretation, and respect physical constraints. The long-term goal is to achieve predictive modeling of these multi-scale systems beyond phenomenologically understanding and establish integrated control across multiple scales.

+ Machine learning methods for multi-scale modeling 
+ Model reduction and stochastic simulation
+ Scientific machine-learning
+ Fluid physics
-->

<!--
My research focuses on computational mathematics, particularly on developing numerical methods for learning partial differential equation (PDE) and stochastic differential equation (SDE) models arising from multi-scale problems. I am interested in designing structure-preserving algorithms that retain essential mathematical properties, such as conservation laws, variational structures, and physical constraints. A central aspect of my work is integrating scientific machine learning (SciML) with numerical analysis to construct accurate and physically interpretable PDE and SDE models of multi-scale systems directly from first-principle descriptions, where conventional approaches often show limitations. 
-->

My research lies at the intersection of computational mathematics, multiscale modeling, and scientific machine learning. I develop mathematical and computational methods for constructing partial differential equations and stochastic models from microscopic first-principles descriptions. A central issue is to identify reduced model classes with sufficient representation ability while preserving conservation laws, dissipative structure, and physical constraints. My work addresses the characterization and constructive representation of these classes, with the goal of establishing physically interpretable models that retain microscopic model fidelity and admit stable, efficient numerical approximation.

Research Interests
===
+ Multi-scale and stochastic modeling
+ Numerical methods for PDEs
+ Scientific machine-learning 
+ Kinetic equations
+ Fluid physics


Collisional Kinetic Equations
===
Collisional kinetic equations describe the transport and relaxation of many-particle systems, but their predictive accuracy depends on how the collision operator represents unresolved interactions and correlations. My work characterizes broader admissible classes of collision operators that preserve conservation laws, entropy production, and physical symmetries. These classes accommodate anisotropic interactions and heterogeneous energy transfer beyond the classical Landau form, enabling accurate predictions of microscopic relaxation and transport in correlated regimes. I develop learning algorithms to construct the generalized collision operator directly from microscopic molecular dynamics. The constructed model enables fast, scalable evaluations and structure-preserving discretizations, and achives accurate prediction of kinetic dynamics across the moderately coupled regimes.


Multiscale Fluids
===
Transferring microscopic physical laws into reliable macroscopic fluid equations remains a central challenge in multiscale modeling. My work develops an extendable variational approach in which the reduced description can be enriched while preserving physical constraints and free-energy dissipation. The variational structure generates constitutive dynamics and stress jointly beyond prescribed empirical closures. This approach establishes a pathway for passing microscopic physical laws across scales and constructing energy-stable macroscopic equations. My current work on polymeric fluids captures nonlinear viscoelastic responses and can be applied to multiscale fluids and kinetic–hydrodynamic reduction.


Mesoscopic Dynamics
===
Mesoscopic descriptions of molecular systems must account for the influence of unresolved dynamics, particularly when scale separation is insufficient. My research develops stochastic reduced models with state-dependent, non-Markovian dynamics to capture many-body memory and heterogeneous dissipation. A main contribution is the construction of extendable memory representations that preserve physical symmetries, fluctuation–dissipation consistency, and equilibrium statistics while admitting efficient simulation. These models provide a broader description of collective transport and molecular relaxation beyond conventional Markovian approximations. 



<!---
While my research is motivated by computational modeling of multi-scale problems, such as molecular, fluid, and kinetic systems, my primary goal is to develop mathematically rigorous and computationally efficient methods for learning and simulating complex dynamical systems. I seek motivated Ph.D. students with a strong background in numerical analysis, applied mathematics, or scientific computing who are interested in developing new numerical methods rather than applying existing techniques to domain-specific applications.
-->


<!--
Research Overview
===

Accurate modeling of multi-scale systems has been a long-standing problem in both computational mathematics and broad scientific applications. A fundamental challenge arises from their multi-scale nature and high-dimensionality. There is generally no simple set of modes that can be used to project and predict the dynamics in a self-contained manner. Existing approaches often rely on sophisticated micro-macro coupling and empirical constitutive closures.  Despite their broad applications, these empirical models generally show limitations in retaining the molecular-level interactions. Currently, there is still a lack of reliable models to quantify complex multi-scale processes by faithfully modeling the micro-interactions in a transferable and integrated manner.

Recent progress in the machine learning (ML) approach, with its unprecedented capability to approximate high-dimensional functions, has opened up many new possibilities in computational science.  Meanwhile, ML is often perceived as a "black-box" approach lacking fundamental principles. This has been an essential obstacle to making further progress in physical modeling and scientific computing. To construct truly reliable ML-models for multi-scale problems, fundamental challenges remain: (1) How to effectively transfer micro-scale physical laws across scales while retaining physical interpretability; (2) How to strictly preserve the physical constraints and mathematical structures of the ML-based partial and ordinary differential equations (PDEs and ODEs) that ensures the well-posedness and numerical stability? 

My research aims to address these challenges by developing numerical algorithms for constructing accurate ML-based models of multi-scale systems directly from first-principle-based descriptions. As part of the AI for Science initiative, a key objective is to retain the micro-model fidelity while strictly preserving canonical structures and symmetry constraints. Examples include hydrodynamics of multi-scale fluids, kinetic transport, and mesoscale stochastic reduced dynamics. The long-term goal is to enable predictive modeling of multi-scale systems that extends beyond phenomenological understanding, facilitating integrated control across multiple scales.
-->




<!--
We are grateful for grant support 
from [NSF](https://www.nsf.gov/), [DOE](https://www.energy.gov/), [Ford](https://www.ford.com/), and [MSU Foundation](https://www.msufoundation.org/). 

<a href="http://www.nsf.gov"><img src="../images/NSF.png" width="120px" alt=""  style="margin-left: 60px"></a><a  href="http://www.energy.gov"><img src="../images/DOE.png" width="100px" alt="" style="horizontal-align:middle;margin:20px 30px"></a>
<a href="http://www.ford.com"><img src="../images/FORD.png" width="125px" alt="" style="horizontal-align:middle;margin:0px 20px"></a><a href="http://www.msufoundation.org/"><img src="../images/MSU_Foundation.jpeg" width="100px" alt="" style="horizontal-align:middle;margin:20px 30px"></a>

-->
