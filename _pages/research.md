---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}


## Computational design of energy storage materials from first-principle

Over the past two decades, Li-ion batteries have enabled society-changing technological advances, especially in portable electronic devices such as smart phones and tablet computers and in electric vehicles.  To keep up with the ever-increasing demands in electrical energy storage, it requires the discovery of high energy density-based cathode materials of lithium-ion rechargeable batteries.

The Li-excess rocksalt cathodes in disordered phase or partially-disordered phase are one of the most promising candidates, as these materials do not require cation chemistry to favor any particular ordering and can be synthesized with a very wide variety of elements. We are interested in computational understanding of the thermodynamical and kinetic properties of the designing of cathode materials.

<img src='/images/drx.png' class="center">



## Statistical mechanics on lattices and disordered systems

First-principles density functional theory (DFT) calculations have been demonstrated as a reliable tool in computational materials science. Despite the increase in computing power and accuracy of DFT methods, the scaling with the number of atoms $\sim O(n^3)$ intrinsically prohibits large-scale calculations (over $10^3$ atoms) or sampling of a high-dimensional occupancy space (millions of structures). This is particularly relevant in systems with configurational degrees of freedom that need to be sampled at non-zero temperature to equilibrate states of partial order, and their associated entropy and free energy.

We are interesed in the cluster expansion method (lattice model), as it has been well developed to describe such configurational energetics for metallic alloys as well as for ionic systems. I am a developer with other [Ceder Group](https://ceder.berkeley.edu/) members for the implementation of computational methods to calculate statistical mechanical and thermodynamic properties of crystalline material systems based on the cluster expansion method from alloy theory and related methods. [[github]](https://github.com/CederGroupHub/smol)

<img src='/images/CE.png' class="center">


## Mathematical programming and optimization for robust computational modeling

To tackle the complex modeling of disordered or partially-disordered systems. The cluster expansion model is parameterized with ab-initio data. The parameterization need to extracts the effective interactions as descriptors of energetics from the information DFT calculations. The well-trained CE model is used to sample the equilibrium states of DRX from Monte Carlo simulations.

To achieve this, a sparse solution with hierarchy constraints (or structural sparsity) is required. We incorperate the idea of  mixded integer programming with lattice model to generate robust and predictive energy models. [[github]](https://github.com/CederGroupHub/sparse-lm)


<img src='/images/sparse.png' class="center">







## Machine learning approaches for data interpretation in materials science

The best is yet to come!

