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
        Materials modeling with atomistic simulations offers a powerful alternative to conventional trial-and-error methods by providing atomic-level insights for mechanistic understanding and accelerated materials discovery. A central objective is to predict material properties at finite temperatures, which requires computationally efficient statistical-mechanics approaches that retain ab initio accuracy.
        <br><br>
        Our research focuses on developing computational frameworks that connect <span style="text-decoration: underline">first-principles descriptions of crystalline and molecular microstates with their macroscopic thermodynamic and kinetic properties.</span>
        By bridging length scales, time scales, and physical phenomena, these frameworks accelerate materials discovery while deepening our fundamental understanding of materials chemistry for technological development.
        <br><br>
        Currently, we are particularly interested in:
        <ul style="list-style-type: disc; padding-left: 40px;">
            <li>Computational modeling of complex materials under realistic experimental conditions.</li>
            <li>Atomistic simulations that integrate statistical mechanics with first-principles calculations.</li>
            <li>Method development in AI for science: simulations for large and open systems, generative dynamics, and experimental alignment.</li>
        </ul>
        </p>
</div>
