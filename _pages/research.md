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
          <p>As my flagship PhD project, I investigate the intricate ion-conduction pathways of the human ATP7B transporter embedded within explicit lipid bilayers. Membrane proteins present unique conformational challenges; to address this, I perform comparative <strong>all-atom MD simulations</strong> to assess how the massive cytoplasmic domain structurally modulates the transmembrane region.</p>
          <p>By coupling <strong>unsupervised machine learning (clustering)</strong> with <strong>multiscale QM/MM MD</strong>, I can pinpoint exactly how domain movements dictate the electronic structure and coordination geometry of the transmembrane Cu-binding sites. Crucially, my computational models are directly correlated with experimental biochemical data to validate the proposed transport mechanisms.</p>
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
        <h3 class="archive__item-title">2. Data-Driven Analysis of Protein-Protein Encounter Complexes</h3>
        <div class="archive__item-excerpt">
          <p>Before copper reaches the membrane, it must be safely transferred from holo-chaperones to the Metal Binding Domain (MBD). In collaborative efforts, I apply multidimensional <strong>machine learning algorithms</strong> to characterize how these Cu(I) binding sites "pre-organize" prior to the handoff.</p>
          <p>By extracting distinct structural ensembles from massive trajectory datasets and validating them with QM/MM calculations, we revealed that initial copper transfer is not purely controlled by electrostatics. Instead, it relies on a delicate, dynamic balance of conformational variability and entropy-enthalpy compensation.</p>
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
