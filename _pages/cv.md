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
**10/2025 - Present**
* **Clinical Partnerships:** Spearheading medical AI projects in collaboration with UNIBAS, CHUV, and HESAV to translate machine learning research into practical, enhanced clinical utility.
* **Full-Stack Engineering ([MSXplain](https://github.com/lluisb3/MSXplain)):** Engineered a complete web application (Python/React) for the automatic segmentation of Multiple Sclerosis (MS) lesions from MRI scans. Integrated automated report generation and ORTHANC/OHIF as PACS and advanced medical visualization.
* **Strategic Leadership (QuantImage):** Managing the evolution of the QuantImage medical ML training platform. Driving architectural upgrades and feature development across both the [backend](https://github.com/medgift/quantimage2-backend) and [frontend](https://github.com/medgift/quantimage2-frontend).
* **LETITIA Project:** Leading data extraction and deep learning initiatives in collaboration with EPFL for complex hospital data processing.

**Researcher Assistant** | HES-SO Valais-Wallis (Sierre, CH)
**09/2023 - 09/2025**
* **QuantImage Operations:** Maintained platform infrastructure, managed SQL databases, and designed new features to improve the interpretability and presentation of application results.
* **Genomic LLMs (Hereditary Project):** Evaluated and synthesized methodologies of state-of-the-art self-supervised models (DNABert, HyenaDNA, Nucleotide Transformer) using omics data. Authored a comprehensive review paper, accepted for publication in the Bioinformatics journal.
* **3D Spatial Analysis (Ither Project):** Utilized HoloLens 2 and customized [Mask3D](https://github.com/lluisb3/Mask3D_v2) for 3D reconstruction and semantic instance segmentation. Extracted Pointcloud/Mesh data using a modified [hl2ss](https://github.com/lluisb3/hl2ss) repository and containerized both algorithms via Docker for system portability.

**Personal Sabbatical & Researcher** | Ireland & Australia
**10/2017 - 03/2020**
* Combined two and a half years of international work experience to explore different cultures and enhance English proficiency, while maintaining academic continuity.
* Continued collaboration with bachelor's thesis supervisor, David Moratal, resulting in the publication: [Link-level functional connectivity neuroalterations in autism spectrum disorder: A developmental resting-state fMRI study](https://www.mdpi.com/2075-4418/9/1/32).

Education
======
* **Joint Master's in Medical Imaging and Applications (MAIA)** | **2021 - 2023**<br>
**Erasmus Mundus Grant.** Univ. of Girona (ES), Univ. of Burgundy (FR), UNICAS (IT)
  * **Master Thesis (HES-SO):** Developed a deep learning model using Self-Supervised Learning and Multiple Instance Learning on 1,000+ Whole Slide Images (1M+ tiles). Publication: Presented results at the SPIE Medical Imaging 2024 conference in San Diego. [[GitHub repository](https://github.com/lluisb3/histo_lung)] [[Proceeding paper](https://www.researchgate.net/publication/379536095_A_full_pipeline_to_analyze_lung_histopathology_images)]
  * **Academic Projects:** Developed multiple CAD systems emphasizing medical image analysis. Repositories: [CAnDy_SkinLesion](https://github.com/lluisb3/CAnDy_SkinLesion), [chest_ct_registration](https://github.com/manasikattel/chest_ct_registration), and [BrainTissue_Segmentation_IBSR18](https://github.com/sofileon/BrainTissueSegmentation_IBSR18).
* **Bachelor's in Biomedical Engineering** | UPV (Valencia, ES) | **2013 - 2017**
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
