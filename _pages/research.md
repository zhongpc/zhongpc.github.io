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

<span style="color:steelblue; font-size:0.8em;">
L. Huang$^{\dagger}$, **P. Zhong**$^{\dagger}$, Y. Ha, Y.-W. Byeon, T.-Y. Huang, Z. Cai, F. Xie, Y. Sun, H. Kim, M. Balasubramanian, B. D. McCloskey, W. Yang, and G. Ceder*, “Optimizing Li-Excess Cation-Disordered Rocksalt Cathode Design through Partial Li Deficiency”, Advanced Energy Materials
(2022).
</span> 

<span style="color:steelblue; font-size:0.8em;">
J. Huang, **P. Zhong**, Y. Ha, Z. Lun, Y. Tian, M. Balasubramanian, W. Yang, and G. Ceder*, “Oxygen vacancy introduction to increase the capacity and voltage retention in Li excess cathode materials”, Small Structures, 2200343 (2022).
</span> 

<span style="color:steelblue; font-size:0.8em;">
J. Huang, **P. Zhong**, Y. Ha, D. Kwon, M. J. Crafton, Y. Tian, M. Balasubramanian, B. D. McCloskey, W. Yang, and G. Ceder, Non-Topotactic Reactions Enable High Rate Capability in Li-Rich Cathode Materials, Nature Energy 6, 706 (2021). </span> 


<span style="color:steelblue; font-size:0.8em;">
**P. Zhong**$^{\dagger}$, Z. Cai$^{\dagger}$, Y. Zhang, R. Giovine, B. Ouyang, G. Zeng, Y. Chen, R. Clément, Z. Lun, and G. Ceder, Increasing Capacity in Disordered Rocksalt Cathodes by Mg Doping, Chem. Mater. 32, 10728 (2020).
</span> 





## Statistical mechanics of lattice systems and optimization for robust modeling

First-principles density functional theory (DFT) calculations have been demonstrated as a reliable tool in computational materials science. Despite the increase in computing power and accuracy of DFT methods, the scaling with the number of atoms $\sim O(n^3)$ intrinsically prohibits large-scale calculations (over $10^3$ atoms) or sampling of a high-dimensional occupancy space (millions of structures). This is particularly relevant in systems with configurational degrees of freedom that need to be sampled at non-zero temperature to equilibrate states of partial order, and their associated entropy and free energy.

We are interested in the cluster expansion method (lattice model), as it has been well developed to describe such configurational energetics for metallic alloys as well as for ionic systems. I worked in a team to develop a CE package [[smol]](https://github.com/CederGroupHub/smol)
capable of handling multi-component ionic systems, where we detailed the mathematical formalism behind CE of ionic systems and presented state-of-the-art training structure sampling, pre-processing, and fitting. Specifically, there are two major issues for ionic systems: (a) how to generate CE models without over-fitting; (b) how to properly sample the configurational space in ionic systems with charge-neutrality. We are interested in how to develop and apply robust modeling to ionic lattice systems.

<img src='/images/sparse.png' class="center">

<img src='/images/CE.png' class="center">


<span style="color:steelblue; font-size:0.8em;">
**P. Zhong**, T. Chen, L. Barroso-Luque, F. Xie, and G. Ceder, An $\ell_0\ell_2$-norm regularized regression model for construction of robust cluster expansion in multicomponent systems, Phys. Rev. B 106, 024203 (2022).
</span> 

<span style="color:steelblue; font-size:0.8em;">
L. Barroso-Luque, **P. Zhong**, J. H. Yang, T. Chen, F. Xie, B. Ouyang, and G. Ceder*, “Cluster expansions of multi-component oxides: Formalism and methods ”, Phys. Rev. B 106, 144202 (2022).
</span> 

<span style="color:steelblue; font-size:0.8em;">
F. Xie, **P. Zhong**, L. Barroso-Luque, B. Ouyang, and G. Ceder*, “Grand-canonical Monte-Carlo simulation methods for charge-decorated cluster expansions”, arXiv:2210.0116 (2022).
</span> 



## Deep-learning modeling for energy materials discovery

> **_NEWS:_**  Welcome to my MRS 2022 poster presentation: “Deep learning of multi-component cathode electrochemistry from experiments”. **DS03.12, Artificial Intelligence for Energy Materials. November 30, 2022, from 8:00 PM to 10:00 PM**

<span style="color:steelblue; font-size:0.8em;">
The best is yet to come.
</span> 


