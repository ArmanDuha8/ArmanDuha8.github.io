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
  (such as photons or atoms) as 1/√N, known as the Standard Quantum Limit (SQL). However, quantumenhanced sensing can leverage entangled states to surpass this      limit and in principle achieve a scaling
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
  structured states in bi-layers. This six-step layerdependent sequence is shown in Fig. 1(b). This
  allows us to overcome limitations on the achievable squeezing, while also lifting restrictions on the
  required interactions, making it accessible in a broader range of platforms.<br>
  I performed extensive numerical calculations using a semiclassical phase-space method known as
  discrete truncated Wigner approximation (dTWA) to simulate the quantum many-body nonequilibrium
  dynamics of the spin model. I wrote my own Python scripts to model the appropriate bilayer and perform
  numerical integration and ran the scripts on an HPC cluster using bash scripts.<br>
  Our results demonstrate that Heisenberg scaling is achievable in this setting beyond the infiniterange interaction case, opening it up to the full range of        power-law interacting systems. Overall we
  show that using spatiotemporal control to engineer the many-body dynamics unlocks the ultimate limit
  of sensitivity in a variety of spin systems.

  
</details>  
![spin_squeezing](/images/spin_squeezing.png)  
### Quantum Transport in Dirac Fermions
Phase transitions in topological material driven by scalar and mass disorder, uncovering rich transport behavior in 2D systems.  
<details>
  <summary>Read more</summary>
  
  In this paper, we have studied the transport properties of a
  massive Dirac fermion in the simultaneous presence of scalar
  potential disorder 1V and mass disorder 1M. Our numerical
  calculations use the real space tight-binding model on a lattice
  with on-site uncorrelated disorder developed by Tworzydło
  et at. We study three different average masses, M¯ ,
  which is interpreted as the band gap. In all three cases, despite
  the band gap, we identify that a critical 1V ∗(M¯ ) exists above
  which the system can no longer be an insulator for any 1M.
  The results support the idea of band gap suppression by onsite Coulomb potential. For 1V < 1V ∗, the system can be in an
  insulating or metallic phase, depending on the 1M value. As
  1M increases, the system exhibits an insulator-to-metal transition at a critical value 1M∗(M¯ , 1V ). We have numerically
  estimated the critical values, 1V ∗, and 1M∗, for different
  M¯ values. Our work demonstrates the interdependent way
  different types of disorders can affect the phases accessible
  to a massive Dirac fermion system.
</details>  
   
![quantum_transport](/images/quantum_transport.png)   

### Lead-Free Perovskite Solar Cells
High-efficiency perovskite tandem solar cell, offering a sustainable alternative to lead-based designs.  
<details>
  In this study, the numerical simulation of a monolithic 2-terminal allperovskite tandem solar cell has been analyzed. The electron affinity of
  the electron and hole transport layers, the cross-section of defects, and
  the thickness of each component were varied using the SCAPS-1D solar
  cell simulator to understand their effect on the PCE. The simulation of
  the tandem device was done with the bottom subcell being illuminated
  with the light filtered by the top subcell, thus ensuring a realistic anal­ysis. Given the current matching condition, our simulation results
  showed that the JSC of the tandem device is limited by the JSC of the
  bottom subcell. Thinning of the top subcell is necessary to match the
  current across the device. While the JSC of the tandem device is smaller
  than the currents of the optimized individual subcells, a high VOC of
  2.63 V in the tandem device results in a significantly higher PCE of
  30.85% compared to that of individual subcells. <br>
  The optimal thickness of the subcells found was 1.6 μm and 983 nm.
  The calculated PCE for those thicknesses will be higher than experi­
  mental values, given that the calculations consider only the dominant
  scattering channel, trap defects at the interface, and ignore scattering at
  grain boundaries. However, if we reduce the thickness of both cells to be
  below 1 μm, we still see a large PCE. For instance, when the thickness of
  the FASnI3 is set to 1 μm, the current matching condition requires the
  layer MAGeI3 to be 961 nm and the results we obtain are that the JSC is
  14.6 mA/cm2, VOC is 2.63 V, FF is 80%, and PCE is reduced from the
  optimal 30.85% to 30.73%. Overall, these results suggest that lead-free
  perovskites can compete with lead-based devices in all-perovskite tan­
  dem solar cells. Further improvement in the performance of the tandem
  device can be achieved by utilizing a bottom subcell that can provide
  higher JSC.
</details>  
   
![solar_cell](/images/solar_cell.png)

Technical Expertise
======
- **Programming:** Python, Mathematica, C++
- **Quantum Simulation:** Discrete truncated Wigner approximation, 2D Dirac fermions modeling
- **Machine Learning:** Symbolic regression for materials science
- **Tools:** Density Functional Theory (DFT), molecular dynamics, HPC clusters

