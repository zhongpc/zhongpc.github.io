---
layout: default
---
<style>
.content-container {
    max-width: 800px;  /* Adjust this value as needed */
    width: 100%;
    margin: 0 auto;
    padding: 20px;
    box-sizing: border-box;
}

.responsive-image {
    width: 100%;
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
}

.aligned-paragraph {
    width: 100%;
    margin-top: 20px;  /* Space between image and paragraph */
}

@media (max-width: 840px) {  /* 800px + 20px padding on each side */
    .content-container {
        width: 95%;  /* Give a little breathing room on smaller screens */
    }
}
</style>

<div class="content-container">
    <img src='/img/PZ_summary.png' class="responsive-image" alt="PZ summary">
    <p class="aligned-paragraph">
        Materials modeling with atomistic simulation offers a powerful alternative to conventional trial-and-error methods by providing atomic-level insights for mechanistic understanding and accelerated material discovery. A central objective is to predict material properties at finite temperatures, which requires a computationally efficient statistical mechanics approach that maintains ab-initio accuracy.
        <br><br>
        Our research focuses on developing and applying advanced computational frameworks that connects first-principles calculations of crystalline and molecular microstates to their macroscopic thermodynamic and kinetic material properties. These computational frameworks enable us to bridge different length scales, time scales, and phenomena, thereby not only accelerating the materials discovery rate but also deepening our fundamental understanding of materials chemistry for technological development. 
        <br><br>
        Currently, we are particularly interested in
        <ul style="list-style-type: disc; padding-left: 40px;">
            <li> Computational modeling of complex materials for renewable energy applications (e.g., Li/Na-ion battery cathodes/electrolytes/interfaces)</li>
            <li>Atomistic simulations with statistical mechanics & first-principles calculations in disordered/amorphous/interfacial systems</li>
            <li>AI for Science: machine learning interatomic potentials, generative models, and reaction networks development & applications</li>
        </ul>
        <!-- We are also a group of computational scientists working closely with experimentalists on materials applications, including energy storage using Li/Na-ion batteries, inorganic synthesis, catalysis, and high-throughput virtual screening for functional molecules/materials, etc. -->
        </p>
</div>