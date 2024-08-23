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

* 2020 Nov-2021 Sep: Research Scientist Intern
  * **Xtalpi AI Research Center**
  * ADMET prediction, Molecular GNN
  * Supervisor: Bowen Zhang

Academic Service
======
* PC member: IEEE BIBM (23, 24)
* Conference reviewer: NeurIPS (24), AMIA (23, 24), BIBM (23, 24)
* Journal reviewr: 

  * ML Journals: Information Fusion, Advanced Engineering Informatics, Expert Systems with Applications, Knowledge-based systems, Patterns, Neural Networks, Neurocomputing.

  * Bioinfo Journals: iMeta, SmartMat, Computers in Biology and Medicine, Briefings in Bioinformatics, Artificial Intelligence in Medicine, Journal of Medical Internet Research.

  * Biomed Journals: Frontiers in Endocrinology, Heliyon, Infectious Disease Modeling, JMIR Formative Research.

Skills
======
* ML package: Pytorch, PyG, DGL
* Comput Chem tool: AMBER, GROMACS, Gaussian, ChimeraX, PyMol, RDkit, Graphein

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