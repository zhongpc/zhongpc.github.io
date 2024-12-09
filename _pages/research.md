---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
---
{% include base_path %}


## Computational design of energy storage materials from first principles

The electric vehicle market for high-energy Li-ion batteries has experienced remarkable growth in recent years. As the demand for electrical energy storage continues to rise, there is an urgent need to discover high-energy-density cathode materials for rechargeable Li-ion batteries. Presently, most cathode materials are based on layered Li(Ni,Mn,Co)O$_2$ (NMC) compounds. However, the high cost of Ni and Co restricts the large-scale application of Li-ion batteries with NMC-type cathodes. The recent emergence of disordered rocksalt cathodes with Li-excess (**DRX**) offers a promising, earth-abundant alternative that could enable Li-ion energy storage to scale up to multiple TWh/year production.

These advanced battery materials often contain numerous elements with significant site disorder, and their short-range ordering (SRO) states have been found to play a critical role in their performance. We are focused on investigating the thermodynamic and kinetic properties of these materials through computational methods, aiming to enhance our understanding and guide the design of optimal cathode materials.



<img src='/images/drx.png' class="center" width="95%">

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

First-principles density functional theory (DFT) calculations have proven to be a reliable tool in computational materials science. However, despite advances in computing power and the accuracy of DFT methods, the scaling with the number of atoms, approximately O(n^3), inherently limits large-scale calculations (over 10^3 atoms) or sampling of high-dimensional occupancy spaces (millions of structures). This limitation is especially relevant in systems with configurational degrees of freedom that require non-zero temperature sampling to equilibrate states of partial order, along with their associated entropy and free energy.

Our interest lies in the cluster expansion method (lattice model), which has been extensively developed to describe configurational energetics for both metallic alloys and ionic systems. In collaboration with a team, we developed a CE package called [[smol]](https://github.com/CederGroupHub/smol), which is capable of handling multi-component ionic systems. In this package, we provide a comprehensive explanation of the mathematical formalism behind the CE of ionic systems and present state-of-the-art techniques for training structure sampling, pre-processing, and fitting. Specifically, we developed several robust lattice modeling techniques and addressed two major challenges in ionic systems: (a) generating CE models without over-fitting, and (b) properly sampling the configurational space in ionic systems while maintaining charge neutrality.

<img src='/images/CE.png' class="center" width="90%">

<span style="color:steelblue; font-size:0.8em;">
**P. Zhong**$^{\dagger}$, F. Xie$^{\dagger}$, L. Barroso-Luque, L. Huang, and G. Ceder$^{\ast}$, “Modeling intercalation chemistry with multi-redox reactions by sparse lattice models in disordered rocksalt cathodes”, arXiv:2307.03717
</span> 

<span style="color:steelblue; font-size:0.8em;">
**P. Zhong**, T. Chen, L. Barroso-Luque, F. Xie, and G. Ceder, An $\ell_0\ell_2$-norm regularized regression model for construction of robust cluster expansion in multicomponent systems, Phys. Rev. B 106, 024203 (2022).
</span> 

<span style="color:steelblue; font-size:0.8em;">
L. Barroso-Luque, **P. Zhong**, J. H. Yang, T. Chen, F. Xie, B. Ouyang, and G. Ceder*, “Cluster expansions of multi-component oxides: Formalism and methods ”, Phys. Rev. B 106, 144202 (2022).
</span> 

<span style="color:steelblue; font-size:0.8em;">
F. Xie, **P. Zhong**, L. Barroso-Luque, B. Ouyang, and G. Ceder$^{\ast}$, “Semigrand-canonical
Monte-Carlo simulation methods for charge-decorated cluster expansions”, Computational Materials Science
218, 112000 (2023).
</span> 



## AI for Science: atomistic modeling, electronic structure, materials science

<span style="color:steelblue; font-size:0.8em;">
**P. Zhong**$^{\ast}$, B. Deng, T. He, Z. Lun, and G. Ceder*, “Deep learning of experimental electrochemistry for battery cathodes across diverse compositions”, arXiv:2304.04986
</span> 

<span style="color:steelblue; font-size:0.8em;">
B. Deng, **P. Zhong**$^{\ast}$, K. Jun, K. Han, C. J. Bartel, and G. Ceder$^{\ast}$, “CHGNet: Pretrained universal neural
network potential for charge-informed atomistic modeling", arXiv:2302.14231
</span> 



<span style="color:steelblue; font-size:0.8em;">
The best is yet to come.
</span> 


