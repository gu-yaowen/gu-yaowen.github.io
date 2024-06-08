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
* Ph.D in **Chemistry(Theoretical & Computational Chemistry)**, New York University, 2023-2028 (expected)
* M.S. in **Medical Informatics**, Peking Union Medical College & Chinese Academy of Medical Sciences, 2020-2023
* B.S. in **Medical Experimental Technology**, Peking University, 2016-2020

Work experience
======
* 2022 Sep-2023 Jan: Research Scientist Intern
  * **SILEXON**
  * Compound-protein Interactin Prediction, Molecular Propertry Prediction.
  * Supervisor: Jianyang Zeng

* 2020 Nov-2021 Sep: Data Scientist (3 months) and Research Scientist (6 months) Intern
  * **Xtalpi AI Research Center**
  * ADMET prediction, Molecular GNN
  * Supervisor: Bowen Zhang

Academic Service
======
* PC member: IEEE BIBM (23, 24)
* Conference reviewer: NeurIPS (24), AMIA (23, 24), BIBM (23, 24)
* Journal reviewr: 
  * ML Journals: Neual Networks, Neurocomputing, Knowledge-based systems, Expert systems with applications.
  * Bioinfo Journals: Briefings in Bioinformatics, Artificial Intelligence in Medicine, Computers in Biology and Medicine
  * Biomed Journals: iMeta, SmartMat, Journal of Medical Internet Research, Infectious Disease Modeling, Haliyon, JMIR Formative Research, Frontiers in Endocrinology.

Skills
======
* ML package: Pytorch, PyG, DGL
* Comput Chem tool: AMBER, GROMACS, ChimeraX, PyMol, RDkit, Graphein

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>