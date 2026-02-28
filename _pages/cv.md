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

Education
======
* **Ph.D. in Computational Biophysics (Final Year)**, [Your University Name], Expected 2026
* **M.Sc. in [Your Subject]**, [Your University Name], [Year]
* **B.Sc. in [Your Subject]**, [Your University Name], [Year]

Research Experience
======
* **PhD Researcher (Computational Biophysics/Biochemistry)**
  * Focus: Computational study of membrane proteins and metal transfer mechanisms.
  * Specialized in MD simulations, QM/MM, and high-level QM calculations.
  * Developed workflows for analyzing protein-protein interactions and binding sites.

Awards & Honors
======
* **IACS Travel Grant (2025/2026)**
  * Competitive funding awarded for presenting research at [Name of Conference].
* [Other fellowships like CSIR-NET/GATE/Institutional Awards]

Technical Skills
======
* **Computational Methods:** * Molecular Dynamics (MD) Simulations
  * QM/MM (Quantum Mechanics/Molecular Mechanics)
  * Ab initio & DFT Calculations
* **Scientific Software:**
  * GROMACS, Amber, Gaussian, ORCA
  * Analysis tools: VMD, PyMOL
* **Programming & Tools:** * Python (Data analysis & Automation), C++
  * Version Control: Git/GitHub
  * Typesetting: LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and Leadership
======
* [Example: Peer reviewer for scientific journals]
* [Example: Seminar coordinator for the research group]
