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

Education
======
* **Master's Degree in Medical Imaging and Applications (MAIA)** (European Erasmus Mundus Grant) | **2021 - 2023**
Universitat de Girona (Spain), University of Burgundy (France) and UNICAS (Italy). <br>
Overall qualification: **9.25/10**
  * Specialized in Image Analysis and Computer Vision using Artificial Intelligence, with a focus on Deep Learning and Machine Learning methods aimed at developing Computer-Aided Diagnosis (CAD) systems.
  * Developed several academic projects, demonstrating expertise in medical image analysis. The main projects with Github repository can be found at [CAnDy_SkinLesion](https://github.com/lluisb3/CAnDy_SkinLesion), [chest_ct_registration](https://github.com/manasikattel/chest_ct_registration), [BrainTissueSegmentation_IBSR18](https://github.com/sofileon/BrainTissueSegmentation_IBSR18).
  * Research Internship at the Hes-SO Valais Wallis to develop my master’s thesis ([HistoLung project](/portfolio/#histolung-project-as-part-of-the-examode-project)).
* **Bachelor’s degree in Biomedical Engineering** | **2013 - 2017**
Universitat Politècnica de València (UPV).<br>
 Overall qualification: **7.10/10**

Work experience
======
**Researcher Assistant** | Hes-SO Valais Wallis (Sierre, Switzerland)
**09/2023 - Present**
* Ither project:
  * Utilized Hololens 2 for 3D reconstruction and instance segmentation of scenes, enhancing spatial data analysis.
  * Extracted Pointcloud and Mesh data from video and depth recordings using a modified [hl2ss GitHub repository](https://github.com/lluisb3/hl2ss).
  * Implemented a customized [Mask3D Github repository](https://github.com/lluisb3/Mask3D_v2) to perform the 3D semantic instance segmentation of the
recorded Pointcloud or Mesh using the Hololens 2 VR.
  * Containerized both algorithms to ensure portability and isolation across different systems using Docker Engine.
* Hereditary project:
  * Conducting research focused on leveraging genomic data to study Amyotrophic Lateral Sclerosis (ALS) and Multiple
Sclerosis (MS) using Deep learning algorithms based on self-supervision learning mainly autoencoders.
  * Adapting the LLMs models (DNABert, HyenaDNA, Nucleotide Transformer) from Hugging Face to work on ALS data.
  * Searching and applying to obtain access to different public genomic datasets (AnswerALS and ProjectMine)
  * Supervising a bachelor’s student in their thesis to continue the work I performed during my research internship.

**Research Internship** | Hes-SO Valais Wallis (Sierre, Switzerland)
**01/2023 - 07/2023**
* Developed Python scripts to automate experiments and data visualization processes.
* Employed self-supervision (MoCo v2) to pre-train a model on Whole Slide Images (digital biopsies) of the lung.
* Trained the pre-trained model using Multiple Instance Learning to classify four different lung cancer subtypes.
* Presented findings at the SPIE Medical Imaging 2024 conference in San Diego. [[GitHub repository](https://github.com/lluisb3/histo_lung)] [[Proceeding paper](https://www.researchgate.net/publication/379536095_A_full_pipeline_to_analyze_lung_histopathology_images)]
* Containerized the hlung model for portability, producing lung cancer predictions and visual heatmaps using Docker
* Managed a dataset with ~1,000 WSI that led after preprocessing to more than 1,000,000 images to train the models.

**Personal sabbatical** | Ireland and Australia
**10/2017 - 03/2020**
* Worked as a chef in Ireland and Australia for two and a half years to broaden life experiences, explore different cultures, and enhance my English language skills.
* Continued collaborating with my bachelor’s thesis supervisor, David Moratal, resulting in the publication: [Link-level functional connectivity neuroalterations in autism spectrum disorder: A developmental resting-state fMRI study](https://www.mdpi.com/2075-4418/9/1/32).

  
Skills
======
* Programming Languages
  * Python, Bash, LateX, Matlab, SQL
* Platforms and Tools
  * Linux, Windows, Docker, Git
* ML/DL Frameworks
  * PyTorch, Hugging Face, TensorFlow, Scikit-learn, Albumentations, Monai, WandB3
* Image Analysis and Computer Vision Libraries
  * OpenCV, Open3D, Openslides, SimpleITK, Scikit-image, QuPath
* Data Analysis Libraries
  * NumPy, SciPy, Pandas, Multiprocessing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  