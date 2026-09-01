---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Education
======

* **Ph.D. in Computer Science**, Aalto University, Finland  
  *2026 - 2029 (expected)*

  Research focus: AI-driven computational biology and molecular design


* **M.S. in Biology**, ShanghaiTech University, China  
  *2023 - 2026*

  GPA: 3.93/4.0 (Major GPA: 3.95/4.0)


* **B.S. in Pharmacy (Basic Pharmacy)**, China Pharmaceutical University, China  
  *2019 - 2023*

  GPA: 3.96/4.0 (Top 3% in major)


Research Interests
======

* Artificial intelligence and machine learning for biological applications
* Generative models for molecular and peptide design
* Structure-based modeling and prediction of biomolecular interactions


Research Experience
======

**AI-Driven De Novo Design of Peptides Targeting NK2R**  
*ShanghaiTech University | Aug 2025 - Dec 2025*

* Performed peptide sequence generation and preliminary screening using BindCraft.
* Optimized candidate sequences using random forest models with ESMC embeddings.
* Designed candidate peptides with predicted ipTM scores above 0.9 in NK2R complexes.


**Construction of a GPCR-Ligand Structural Dataset and Its Application**  
*ShanghaiTech University | Dec 2024 - Present*

* Constructed a GPCR-ligand complex structural dataset using template-based modeling and AlphaFold3.
* Developed deep learning models to improve virtual screening performance for GPCR targets.
* Investigated computational approaches for understanding ligand regulation mechanisms.


**Identification and Characterization of Activation Features in OR5AN1**  
*ShanghaiTech University | Dec 2024 - Oct 2025*

* Analyzed residue-residue contact patterns to identify activation features in olfactory receptors.
* Developed structure-based molecular representations for odorant recognition analysis.


**Decoding Ligand Selectivity in Insect Olfactory Receptors**  
*ShanghaiTech University | Nov 2023 - Feb 2024*

* Applied Bayesian Gaussian mixture models and hidden Markov models to analyze receptor sequence and ligand selectivity.
* Identified receptor classes and potential residues responsible for ligand recognition.


**Computational Investigation of Structural Components from Moutan Cortex in Acute Lung Injury Treatment**  
*China Pharmaceutical University | Dec 2022 - Aug 2023*

* Developed a computational framework integrating target prediction, molecular docking, network analysis, UMAP, and enrichment analysis.
* Validated computational predictions through biological experiments.


Publications
======

<ul class="publication-cv-list">
{% for post in site.publications reversed %}
  {% include archive-single-publication-cv.html %}
{% endfor %}
</ul>


Talks & Presentations
======

<ul class="talk-cv-list">
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>


Honors & Awards
======

<ul class="award-cv-list">
{% for post in site.awards reversed %}
  {% include archive-single-award-cv.html %}
{% endfor %}
</ul>

Teaching Experience
======

**Teaching Assistant, Computational Biology**  
ShanghaiTech University  
*Feb 2024 – Jun 2024*

* Developed teaching materials and solutions for sequence analysis, profile HMMs, SSN/GNN construction, and phylogenetic modeling.
* Mentored undergraduate students in Linux and computational biology workflows.


Leadership & Service
======

**Vice Director, Academic Development Division**  
Student Affairs Committee, School of Life Science and Technology, ShanghaiTech University

* Organized first-author forums with principal investigators and researchers.
* Co-organized academic salon events with institutions including the Chinese Society for Cell Biology.


**Rotating Chair**  
Student Leadership Board, iHuman Institute, ShanghaiTech University

* Coordinated student academic activities and facilitated communication between students and faculty members.

Skills
======

**Programming & Machine Learning**

* Python, PyTorch, scikit-learn, MATLAB, R
* Shell scripting, Git, Markdown, LaTeX


**Computational Biology & Chemistry**

* AlphaFold3, RDKit, Open Babel
* GROMACS, VMD, Gaussian
* Schrödinger Suite, ChemOffice, PySCF


**High-Performance Computing**

* LSF, SLURM
* Docker, Apptainer, Dask


Languages
======

* English (TOEFL: 95)
* Chinese (Native)
