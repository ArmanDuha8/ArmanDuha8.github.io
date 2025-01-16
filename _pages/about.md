---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a computational condensed matter and AMO physicist with a passion for exploring quantum many-body dynamics, quantum simulation, and topological materials. My research focuses on advancing quantum technologies through a combination of analytical and numerical approaches, leveraging cutting-edge computational tools to tackle complex problems in quantum transport, entanglement generation, and material optimization.
Currently pursuing my Ph.D. in Physics at Oklahoma State University, I aim to bridge theory and experiment to unlock new possibilities in quantum sensing, information, and materials science.

Research Interests
======
- **Quantum Many-Body Dynamics:** Studying out-of-equilibrium phases, entanglement generation, and quantum-enhanced sensing.
- **Quantum Simulation:** Leveraging ultra-cold atoms and Floquet-engineered spin systems for innovative quantum platforms.
- **Topological Materials:** Exploring transport phenomena in 2D materials, novel phases of matter, and quantum computing.
- **Material Optimization:** Performing first-principles calculations, DFT molecular dynamics for renewable energy sources.

Featured Research Projects
======


### Power-Law Interacting Spin Models
Heisenberg-limited entanglement generation in spin-1/2 XXZ models using Floquet engineering for quantum-enhanced sensing.     
<details>
  <summary>Read more</summary>
  In classical sensing, the sensitivity of measurements improves with the number of particles or resources
  (such as photons or atoms) as 1/√N, known as the Standard Quantum Limit (SQL). However, quantum-enhanced sensing can leverage entangled states to surpass this      limit and in principle achieve a scaling
  of 1/N, referred to as the Heisenberg limit, by maximizing the generation of metrologically useful
  1entanglement. To that end, engineering the many-body dynamics of quantum systems to maximize
  the generation of useful entanglement is a critical goal for fulfilling the promise of quantum advantage.
  One particularly promising avenue is quantum spin systems, which can now be manipulated along the
  complementary axes of time and space, opening up new scopes for engineering their quantum dynamics.<br>
  In this work[1] with my supervisor Thomas
  Bilitewski, we show that combining spatial and
  temporal control enables Heisenberg-limited scaling of two-mode squeezing in power-law interacting spin models, currently accessible in a broad
  range of quantum platforms. Specifically, I work
  with a power-law interacting bilayer XXZ spin
  model, shown schematically in Fig. 1(a). The role
  of interlayer spin-exchange interactions ( V ⊥,AB
  ij )
  in this model is to create entangled pairs of flipped
  spins, whereas the interlayer Ising interactions (
  V z,AB
  ij ) will energetically penalize the creation of
  spin flips. We use Floquet pulse-sequence to engineer spin-spin interactions adapted to spatially
  structured states in bi-layers. This six-step layer-dependent sequence is shown in Fig. 1(b). This
  allows us to overcome limitations on the achievable squeezing, while also lifting restrictions on the
  required interactions, making it accessible in a broader range of platforms.<br>
  I performed extensive numerical calculations using a semiclassical phase-space method known as
  discrete truncated Wigner approximation (dTWA) to simulate the quantum many-body nonequilibrium
  dynamics of the spin model. I wrote my own Python scripts to model the appropriate bilayer and perform
  numerical integration and ran the scripts on an HPC cluster using bash scripts.<br>
  Our results demonstrate that Heisenberg scaling is achievable in this setting beyond the infinite range interaction case, opening it up to the full range of        power-law interacting systems. Overall we
  show that using spatiotemporal control to engineer the many-body dynamics unlocks the ultimate limit
  of sensitivity in a variety of spin systems.
  ![spin_squeezing](/images/spin_squeezing.png)  


  
</details>  



  
Universal Scaling of Two-mode Squeezing in Power-Law Interacting Spin Models
<details>
<summary>Read more</summary>
  In our previous work discussed above, we showed that power-law interacting spin-1/2 XXZ models allow scalable generation of entanglement in the form of            two-mode squeezing and thus achieves
  Heisenberg limited squeezing. Crucially, this depends on each spin layer behaving collectively, which
  requires sufficiently strong intra-plane and sufficiently homogeneous inter-layer interactions.
  In my current project with Thomas Bilitewski and in collaboration with our group’s postdoc Samuel
  Begg, I focus on the transition from dynamics characterized by Heisenberg limited squeezing to nonfully collective behavior in 1D (spin ladder) and 2D (spin       bilayer) systems for a range of power-law
  interaction exponents. We identify a universal scaling of the generated squeezing in terms of system
  parameters and identify distinct phases as a function of dimensionality, power-law exponent, and aspect
  ratio of the system. We are currently at the manuscript preparation stage for this project.
  This study offers a comprehensive framework for engineering collective quantum states in experimental platforms that realize power-law spin models, advancing      applications in quantum sensing and
  simulation.
</details>  

### Quantum Transport in Dirac Fermions
Phase transitions in topological material driven by scalar and mass disorder, uncovering rich transport behavior in 2D systems.  
<details>
  <summary>Read more</summary>
  
  Two-dimensional Dirac fermions, particularly those found in topological materials, have promising applications in areas like spintronics, quantum computing,       and optoelectronics due to robust surface
  conducting states with Dirac fermions that are protected against perturbations, allowing for highly
  efficient charge and spin transport with minimal dissipation. On the other hand, the unique nature of
  Dirac fermions can lead to unusual quantum transport phenomena, including quantized conductance
  and absence of metal-insulator transition under certain disorder types.<br>
  In this project, with my co-advisor Mario Borunda, I analyzed how the combination of scalar
  potential and mass disorder affects the transport properties of Dirac fermions. Using a tight-binding
  model on a lattice with uncorrelated on-site disorder, I calculated the conductivity from the transmission
  eigenvalues via the Landauer formula. For this, I wrote my own Mathematica scripts that model the
  lattice structure and calculate the eigenvalues.<br>
  Our results demonstrate that combining these two types of disorder leads to rich phase behavior,
  including insulating, scale-invariant, and metallic phases. The phases emerge at critical values of scalar
  potential and random mass (gap) disorder. Such disorders can be engineered by controlling the sample’s
  charge fluctuation which depends on the level of impurity. For multilayer systems like bilayer graphene
  or graphene on h-BN, the unprecedented precision in controlling twist angle and interlayer distance
  enables fine-tuning of interlayer coupling, which, along with gate voltage, determines the mass disorder.<br>
  Motivated by these experimentally realizable controls, I investigated a broad disorder landscape,
  identifying the critical disorder strengths at which the phase transitions occur. Our work highlights
  the interdependent way different types of disorders can affect the phases accessible to a massive Dirac
  fermion system and how tuning the disorders can control its transport behavior.
</details>  
   
![quantum_transport](/images/quantum_transport.png)   

### Lead-Free Perovskite Solar Cells
High-efficiency perovskite tandem solar cell, offering a sustainable alternative to lead-based designs.  
<details>
  During the early stage of my Ph.D. before moving on to work with topological materials and spin
  models, I worked on numerically simulating solar cells and their optimization.<br>
  In this project[3] under the supervision of my co-advisor Mario Borunda, I used a numerical solar
  cell simulation tool, SCAPS, which solves the Poisson equation and the continuity equations for charge
  carriers (electrons and holes) to compute the electrostatics and transport properties within the solar cell.
  I modeled a tandem solar cell consisting of the perovskite subcells, MAGeI3 and FASnI3. Perovskite solar
  cells (PSCs) have gained significant attention in recent years due to their rapid efficiency improvements,
  cost-effectiveness, and versatility in parameter tuning. However, some of the best-performing perovskite
  materials contain lead, raising concerns about environmental impact and toxicity.<br>
  I addressed this challenge by working with lead-free perovskites and performing extensive numerical
  simulations to explore the parameter space of optoelectrical properties such as band gap, charge mobility, dielectric permittivity, etc. Our results show that     after optimization, 31% efficiency is reached,
  suggesting lead-free perovskites can compete with lead-based devices.
</details>  
   
![solar_cell](/images/solar_cell.png)

Technical Expertise
======
- **Programming:** Python, Mathematica, C++
- **Quantum Simulation:** Discrete truncated Wigner approximation, 2D Dirac fermions modeling
- **Machine Learning:** Symbolic regression for materials science
- **Tools:** Density Functional Theory (DFT), molecular dynamics, HPC clusters

