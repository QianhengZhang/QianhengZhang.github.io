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
**University of Wisconsin-Madison**

_Ph.D. in Geography/Environment (GeoAI, ML, and LLMs for Spatial & Human Data), Exp. 05/2028_


_M.S. in Cartography/Geographical Information System, GPA: 3.91/4.0_  05/2025


_Double M.S. in Computer Science (expected 2026)_
09/2023 - Exp. 05/2028

**University of Washington-Seattle**

_Bachelor of Art Geography: Data Science, GPA: 3.81/4.0_
09/2019 - 03/2023

Research Experience
======
**Lead Developer | OSU ICICLE Program - GNN Food Flow**
_January 2025 – Present_
- Built scalable data and training pipelines for GNN-based prediction of 10M+ food flows, leveraging distributed computing on HPC clusters. Prototyped models with PyTorch and optimized performance metrics (AUC 0.82, R² 0.36).
- Using inference results in flow volume regression across food categories, with developing open-source outputs for national-scale infrastructure resilience studies.

**Lead Researcher | GeoAnalystBench Project**
_October 2024 – Present_
- Developed and deployed a benchmark of 50+ tasks to evaluate LLMs (Transformer-based architectures) on reasoning and code generation; designed data pipeline and evaluation framework (CodeBLEU, workflow metrics).
- Designed the evaluation framework using metrics like CodeBLEU and workflow difference to measure alignment between LLM and human reasoning; results showed proprietary LLMs outperformed open-source models on task structure and semantic flow.
- Categorized tasks into applied spatial analysis types (e.g., "Determining Relationships", "Predictive Modeling"), revealing that LLM performance varies significantly across GIS domains.

**Researcher | Urban Wildlife & Human Mobility**
_September 2024 – Present_
- Led a study analyzing over 5,000 coyote sightings with multi-scale human mobility data (SafeGraph) in Los Angeles County during and after the COVID-19 pandemic.
- Framed an ambiguous ecological question (coyote-human interactions post-Covid) into ML tasks; applied SEM and GWR for spatiotemporal modeling, integrating human mobility data.
- Discovered significant inflow/outflow effects on urban coyote presence, demonstrating behavioral plasticity to human movement.

**Research Assistant | OSU ICICLE Program - ScienceAgentBench**
_April 2024 - October 2024_
- Designed and annotated 25+ complex GIS and spatial reasoning tasks to benchmark large language models on geospatial intelligence.
- Contributed to a 15% improvement in GIS-specific LLM task accuracy through the design of reproducible workflows and evaluation scripts.
- Developed a taxonomy of spatial agent task types to improve the scientific rigor of GIS AI benchmarks.

<!-- Selected Publications
======
- Chen Z, Chen S, Ning Y, Zhang, Q., et al (2025, April). ScienceAgentbench: Toward rigorous assessment of language agents for data-driven scientific discovery. *International Conference on Learning Representations 2025*.
- Zhang, Q., Gao, S., Chen, W., Zhao, Y., Nie, Y., Chen, Z., Chen, S., Su, Y., Sun, H. (2025). GeoAnalystBench: A GeoAI benchmark for assessing large language models for spatial analysis workflow and code generation. *Transactions in GIS*. [In Press]
- Zhang, Q., Paul, D., Miller, M., Morales, M., Gao, S. (2025). Scalable Inter-County Food Flow Prediction Using Graph Neural Networks [Application]. *Proceedings of the 33rd ACM International Conference on Advances in Geographic Information Systems*.
- Zhang, Q., Kang, Y., & Roth, R. (2023). The Ethics of AI-Generated Maps: DALL· E 2 and AI’s Implications for Cartography (Short Paper). In *12th International Conference on Geographic Information Science (GIScience 2023)*. Schloss-Dagstuhl-Leibniz Zentrum für Informatik. -->

{% if site.publications %}
<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>
{% endif %}

Conferences Talks
======
<!-- **Oral Presentation**
- *Scalable Inter-County Food Flow Prediction Using Graph Neural Network*
  ACM 2025 SigSpatial, Minneapolis, Minnesota, United States, 11/2025
- *Automating Geospatial Analysis Workflows Using ChatGPT-4*
  ACM 2024 SigSpatial, Atlanta, Georgia, United States, 10/2024
- *Enhancing Wildlife Classification Accuracy in Camera Trap Images using GIS-Enhanced Federated Machine Learning Approaches*
  AAG 2024 Annual Meeting, Honolulu, Hawaii, United States, 04/2024
- *The Ethics of AI-Generated Maps: DALL· E 2 and AI’s Implications for Cartography*
  The 12th International Conference on GIScience, Leeds, United Kingdom, 09/2023 -->

{% if site.talks %}
<ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}
</ul>
{% endif %}

Grants & Awards
======
- NSF Student and Early Career Scholarships, 08/2025
- Trewartha Research Awards, University of Wisconsin-Madison, 03/2025
- I-Guide Summer School Travel Awards, 08/2024
- ESRI User Conference Student Assistantship, 07/2024
- Trewartha Conference Travel Awards, University of Wisconsin-Madison, 03/2024
- Dean’s List, University of Washington-Seattle, 01/2020 - 03/2023

Teaching
======
{% if site.teaching %}
<ul>
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>
{% endif %}

Skills
======
- **Programming:** Python (Proficient), SQL, R, Java, JS
- **ML/AI Frameworks:** PyTorch, HuggingFace Transformers
- **Specialized:** LLMs, GNNs, CNNs, data & training pipelines, distributed ML (HPC, AWS/GCP basics)
- **Other:** ArcGIS/QGIS, visualization (Tableau, Illustrator, Figma), Docker, Git

Service and Leadership
======
- Member, GeoDS Lab, UW–Madison
- Reviewer, ACM SigSpatial Workshop, IJGIS
