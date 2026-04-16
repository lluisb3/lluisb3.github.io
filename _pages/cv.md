---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="wordwrap">You can also find a copy of my CV <a href="../files/CV_Lluis.pdf">here</a>.</div>

Relevant Experience
======
**Academic Collaborator** | HES-SO Valais-Wallis (Sierre, CH)
**Oct/2025 – Present**
* **Full-Stack Engineering (MSXplain w/ UNIBAS, EPFL, UNIL):** Engineered a complete web application (Python/React) for the automatic segmentation of Multiple Sclerosis (MS) lesions from MRI scans. Integrated automated report generation and ORTHANC/OHIF as PACS and advanced medical visualization.
* **Strategic Leadership (QuantImage):** Managing the evolution of the QuantImage medical ML training platform. Driving architectural upgrades and feature development across both the [backend](https://github.com/medgift/quantimage2-backend) and [frontend](https://github.com/medgift/quantimage2-frontend).
* **Clinical AI & Data Engineering:** Leading the extraction and depersonalization of longitudinal hospital data (LETITIA project w/ EPFL, CHUV) to build and validate medical AI prototypes. Concurrently assisting Master's students by engineering the machine learning pipelines for their radiomics research.

**Researcher Assistant** | HES-SO Valais-Wallis (Sierre, CH)
**Sep/2023 – Sep/2025**
* **QuantImage Operations:** Maintained platform infrastructure, managed SQL databases, and designed new features to improve the interpretability and presentation of application results.
* **Genomic LLMs (Hereditary Project):** Evaluated and synthesized methodologies of state-of-the-art self-supervised models (DNABert, HyenaDNA, Nucleotide Transformer) using omics data. Authored a comprehensive review paper, accepted for publication in the Briefings in Bioinformatics journal.
* **3D Spatial Analysis (Ither Project):** Utilized HoloLens 2 and customized [Mask3D](https://github.com/lluisb3/Mask3D_v2) for 3D reconstruction and semantic instance segmentation. Extracted Pointcloud/Mesh data using a modified [hl2ss](https://github.com/lluisb3/hl2ss) repository and containerized both algorithms via Docker for system portability.

**International Experience & Independent Research** | Ireland & Australia
**Oct/2017 – Mar/2020**
* **Professional Growth:** Relocated to Ireland and Australia to achieve Professional English Proficiency (C1). Managed high-pressure duties as a chef, developing resilience and strong teamwork in fast-paced environments.
* **Scientific Continuity:** Maintained research collaboration with Prof. David Moratal, resulting in a peer-reviewed publication: [Link-level functional connectivity neuroalterations in autism spectrum disorder: A developmental resting-state fMRI study](https://www.mdpi.com/2075-4418/9/1/32).

Education
======
* **Joint Master's in Medical Imaging and Applications (MAIA)** | **2021 – 2023**<br>
**Erasmus Mundus Grant.** Univ. of Girona (ES), Univ. of Burgundy (FR), UNICAS (IT)
  * **Master Thesis (HES-SO):** Developed a deep learning model using Self-Supervised Learning and Multiple Instance Learning on 1,000+ Whole Slide Images (1M+ tiles). Publication: Presented results at the SPIE Medical Imaging 2024 conference in San Diego. [[GitHub repository](https://github.com/lluisb3/histo_lung)] [[Proceeding paper](https://www.researchgate.net/publication/379536095_A_full_pipeline_to_analyze_lung_histopathology_images)]
  * **Academic Projects:** Engineered deep learning pipelines for complex medical image analysis, specifically executing image classification ([CAnDy_SkinLesion](https://github.com/lluisb3/CAnDy_SkinLesion)), image registration ([chest_ct_registration](https://github.com/manasikattel/chest_ct_registration)), and semantic segmentation ([BrainTissue_Segmentation_IBSR18](https://github.com/sofileon/BrainTissueSegmentation_IBSR18)).
* **Bachelor's in Biomedical Engineering** &mdash; UPV (Valencia, ES) &mdash; **2013 – 2017**
  * Focus: Specialized in Medical Image Analysis and Machine Learning methods aimed at developing Computer-Aided Diagnosis (CAD) systems.

Technical Skills
======
* **Programming:** Python, JavaScript (React), SQL, Bash, LaTeX, MATLAB
* **Machine & Deep Learning:** PyTorch, Hugging Face, TensorFlow, Scikit-learn, MONAI, Weights & Biases (WandB)
* **Agentic AI & Dev Tools:** Claude Code, GitHub Copilot Pro, Docker, Git, Linux
* **Computer Vision & Medical:** OpenCV, Open3D, SimpleITK, QuPath, OpenSlide, Albumentations
* **Data & Compute:** CUDA, Multiprocessing, NumPy, Pandas, SciPy

Language Proficiency
======
* **Spanish:** Native
* **Catalan:** Native
* **English:** Professional Competence (C1 level, APTIS)
* **French:** Intermediate
* **Italian:** Intermediate

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
