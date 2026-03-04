---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download Full CV as PDF]({{ site.baseurl }}/assets/pdfs/CV_Sk_Hasibo_Hassan.pdf){: .btn .btn--primary}

### Professional Summary
**Computational Biophysicist** specializing in the multiscale modeling of biological metal trafficking. Expert in integrating **all-atom molecular dynamics**, **QM/MM simulations**, and **machine learning** to elucidate Cu(I) transfer mechanisms in membrane proteins (**ATP7B**) and chaperone-to-MBD delivery pathways. My work bridges protein dynamics, coordination chemistry, and explicit solvation to resolve complex mechanistic problems in metallo-biochemistry.

Education
======
* **Ph.D. in Computational Biophysics**, Indian Association for the Cultivation of Science (IACS), Kolkata (Expected 2026)
  * *Thesis:* Understanding Molecular Mechanism of Cellular Copper Trafficking
* **M.Sc. in Chemistry**, Indian Institute of Engineering Science and Technology (IIEST), Shibpur (2017)
* **B.Sc. in Chemistry**, Bagnan College, University of Calcutta, Kolkata (2015)

Research Experience
======
**PhD Research Scholar** | *IACS, Kolkata* (2020 -- Present)
* **Membrane Proteins & Ion Transport:** Modeled ATP7B binding sites using comparative all-atom MD and multiscale QM/MM to understand cytoplasmic pre-organization and copper uptake.
* **Data-Driven Biophysics:** Applied unsupervised machine learning (tICA, Clustering) to high-dimensional trajectories to identify rare conformational states and reaction intermediates in protein-protein complexes.
* **Quantum Mechanistic Studies:** Investigated biological Cu(I) transfer pathways and protonation states using DFT-based quantum chemistry and hybrid classical MD/static QM explicit solvation modeling.

**Masters Researcher** | *IIEST, Shibpur* (2016 -- 2017)
* Mapped theoretical potential energy surfaces for ammonia activation mediated by cobalt complexes using high-level quantum chemistry.

Technical Expertise
======
* **Computational Methods:** Molecular Dynamics (MD), QM/MM, Ab initio/DFT Calculations, Enhanced Sampling, Collective Variables.
* **Data Science & ML:** Unsupervised & Supervised Learning, Dimensionality Reduction (TICA, PCA), Scikit-learn.
* **Simulation & Quantum Suites:** NAMD, OpenMM, ORCA, GAUSSIAN, CP2K.
* **Programming & HPC:** Python (Advanced), FORTRAN, Bash, Linux environments, PBS job scheduling, GPU-accelerated simulations.
* **Analysis:** MDAnalysis, VMD (Tcl/Tk), PyMOL, Matplotlib.

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Conferences & Advanced Training
======
* **Gordon Research Conference (GRC):** Mechanisms of Membrane Transport, Switzerland (May 2025)
* **Workshops:** Machine Learning Specialization (DeepLearning.AI/Stanford), AI/ML in Statistical Mechanics, Advanced In Silico Drug Design.

Fellowships & Honors
======
* **IACS Travel Grant (2025):** Awarded competitive funding to present research at the Gordon Research Conference.
* **National Examinations:** CSIR-NET (2020), GATE (2017), IIT-JAM (2015).

Teaching Experience
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
