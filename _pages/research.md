---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}


## Computational design of energy storage materials from first-principle

The electric-vehicle market for high-energy Li-ion batteries has witnessed tremendous growth over the past years. The increasing demands in electrical energy storage require the discovery of high energy density-based cathode materials of rechargeable Li-ion batteries. Current cathode materials are mostly confined to the layered Li(Ni,Mn,Co)O$_2$ (NMC). The high cost of Ni and Co limits the very large-scale application of Li-ion batteries with NMC-type cathodes. The recent development of disordered rocksalt cathodes with Li-excess (DRX) is another promising earth-abundant cathode material, which can enable scaling of Li-ion energy storage to many TWh/year production.

Such modern battery materials can contain a large number of elements with substantial site disorder, and their state of short-range ordering (SRO) has been shown to be critical for their performance. We are interested in computational understanding of the thermodynamic and kinetic properties for the designing of cathode materials.

<img src='/images/drx.png' class="center">



## Statistical mechanics on lattices and disordered systems

First-principles density functional theory (DFT) calculations have been demonstrated as a reliable tool in computational materials science. Despite the increase in computing power and accuracy of DFT methods, the scaling with the number of atoms $\sim O(n^3)$ intrinsically prohibits large-scale calculations (over $10^3$ atoms) or sampling of a high-dimensional occupancy space (millions of structures). This is particularly relevant in systems with configurational degrees of freedom that need to be sampled at non-zero temperature to equilibrate states of partial order, and their associated entropy and free energy.

We are interested in the cluster expansion method (lattice model), as it has been well developed to describe such configurational energetics for metallic alloys as well as for ionic systems. I worked in a team to develop a CE package [[smol]](https://github.com/CederGroupHub/smol)
capable of handling multi-component ionic systems, where we detailed the mathematical formalism behind CE of ionic systems and presented state-of-the-art training structure sampling, pre-processing, and fitting. [[ref]](https://journals.aps.org/prb/pdf/10.1103/PhysRevB.106.144202)
<img src='/images/CE.png' class="center">


## Mathematical programming and optimization for robust computational modeling

To tackle the complex modeling of disordered or partially-disordered systems. The cluster expansion model is parameterized with ab-initio data. The parameterization needs to extract the effective interactions as the informative descriptors of energetics from the DFT calculations. The well-fitted CE model is used to sample the equilibrium states from Monte Carlo simulations.

To achieve this, a sparse solution with hierarchy constraints (or structural sparsity) is required. We incorporate the idea of mixed integer programming with a lattice model to generate robust and predictive energy models. [[github]](https://github.com/CederGroupHub/sparse-lm) [[ref]](https://ceder.berkeley.edu/publications/2022_zhong_l0l2_fitting.pdf)


<img src='/images/sparse.png' class="center">




## Deep-learning modeling for energy materials discovery

> **_NEWS:_**  Welcome to my MRS 2022 poster presentation: “Deep learning of multi-component cathode electrochemistry from experiments”. **DS03.12, Artificial Intelligence for Energy Materials. November 30, 2022, from 8:00 PM to 10:00 PM**



