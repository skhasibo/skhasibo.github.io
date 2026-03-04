---
title: "Research"
layout: single
permalink: /research/
author_profile: true
---

My research lies at the intersection of **Computational Biophysics** and **Bioinorganic Chemistry**, with a primary focus on the structural dynamics and transport mechanisms of complex membrane proteins. By bridging the gap between classical all-atom simulations, unsupervised machine learning, and high-level quantum chemistry, I aim to uncover the fundamental molecular principles governing cellular copper trafficking.

---

<div class="entries-list">

  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="{{ site.baseurl }}/images/human_mbd6.png" alt="ATP7B Membrane Protein Simulation">
      </div>
      <div class="archive__item-body">
        <h3 class="archive__item-title">1. Mechanism of Copper Transport in the ATP7B Membrane Protein</h3>
        <div class="archive__item-excerpt">
          <p>My PhD research focuses on understanding how the human ATP7B membrane transporter mediates copper translocation across biological membranes. I perform <strong>all-atom molecular dynamics simulations</strong> of ATP7B embedded in explicit lipid bilayers to capture the conformational dynamics of this large P-type ATPase. A central question in my work is how the massive cytoplasmic domains regulate the transmembrane copper-binding sites. To address this, I integrate <strong>machine learning–based ensemble analysis</strong>, <strong>enhanced sampling strategies</strong>, and <strong>multiscale QM/MM simulations</strong> to systematically connect large-scale domain motions with changes in coordination geometry and electronic structure at the metal center.</p>
          <p>By integrating classical MD, electronic structure calculations, and experimental biochemical data, my research establishes a mechanistic link between membrane-embedded conformational dynamics and metal transport function.</p>
        </div>
      </div>
    </article>
  </div>

  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="{{ site.baseurl }}/images/adduct2_final.png" alt="Protein-Protein Encounter Complex">
      </div>
      <div class="archive__item-body">
        <h3 class="archive__item-title">2. Copper Transfer and Protein-Protein Dynamics</h3>
        <div class="archive__item-excerpt">
          <p>Before copper reaches the membrane transporter ATP7B, it must be transferred from holo-chaperones to the Metal Binding Domain (MBD). In a collaborative project within our group, I investigated whether protonation changes or protein–protein interactions govern this early-stage Cu(I) transfer.</p>
          <p>Using DFT calculations and molecular dynamics simulations, we demonstrated that copper transfer is primarily driven by interfacial preorganization and direct thiol coordination, while deprotonation involves a significant energetic barrier. Extending this work, I applied machine learning–based ensemble analysis with QM/MM validation to characterize encounter complex dynamics, revealing that metal transfer depends on conformational variability and entropy–enthalpy balance rather than purely electrostatic effects.</p>
        </div>
      </div>
    </article>
  </div>

  <div class="list__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="{{ site.baseurl }}/images/solvation_qm.png" alt="QM/MM and Explicit Solvation">
      </div>
      <div class="archive__item-body">
        <h3 class="archive__item-title">3. Quantum Mechanistic Studies: Solvation & Protonation States</h3>
        <div class="archive__item-excerpt">
          <p>Accurate metallo-biochemistry requires rigorous physical chemistry. To understand the fundamental rules of biological copper exchange, I developed a <strong>hybrid classical MD-static QM approach</strong> to accurately capture fluctuating explicit solvation shells. This method identified thiol deprotonation as the rate-determining step in aqueous copper exchange.</p>
          <p>Applying this framework to protein systems, I used <strong>DFT-based quantum chemistry</strong> to investigate cysteine protonation states during chaperone-mediated transfer. The findings challenge traditional assumptions, demonstrating that early-stage transfer is driven by direct thiol coordination and protein-protein interactions rather than local pKa shifts.</p>
        </div>
      </div>
    </article>
  </div>

</div>
### Key Methodologies
* **Quantum Chemistry:** DFT, pKa calculations, and QM/MM for reaction pathways.
* **Classical MD:** Solvent effects, protein-protein docking, and membrane protein simulations.
* **Statistical Mechanics:** Markov State Models (MSM) for long-time kinetics and free energy landscapes.
