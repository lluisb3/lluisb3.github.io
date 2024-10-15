---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
redirect_from:
  - /portfolio
---

{% include base_path %}

---

ITHER project
======

 <div style='text-align: justify'> ITHER - Home-based and data driven therapy for adolescents with hyperactivity and/or autism leveraging mixed reality. The goal of the ITHER project is to develop a room-scale multi-sensory mixed reality (MR) exercises combining context-aware visual, and 3D audio with passive haptic feedback using everyday objects available in all homes. As part of the team I was in charge of computing the 3D reconstruction of a scene recorded using the Hololens 2 headset. Afterwards, perform the 3D semantic instance segmentation of common objects that could be included in the MR game as passive haptic feedback. </div>
 
 As an example, this is a scene we want to digitally reconstruct and 3D segment common objects present on it:

 <img src='/images/scene_real.jpg'> 

  <div style='text-align: justify'> In the following animation are presented the outputs from the 2 different algorithms. First the 3D reconstruction of the scene in from of a Point Cloud using the Hololens 2 headset (<a href='https://github.com/lluisb3/hl2ss'>hl2ss</a>). Second using AI (<a href='https://github.com/lluisb3/Mask3D_v2'>Mask3D</a>) from the 3D Point Cloud I compute the 3D instance segmentation of some common objects. For example you can see how the chairs as segmented as yellow objects, the bookshelves as purple, the table as light red, 2 doors as red and, the windows as light purple. </div>

 <div style='text-align: center'> <img src='/images/scene1_combined.gif'> </div> 

---
  
Hereditary UE Horizon project
======

<p><div style='text-align: justify'> HEREDITARY (HetERogeneous sEmantic Data integratIon for the guT-bRain interplaY) is an interdisciplinary project aimed at improving healthcare by integrating diverse health data to uncover insights into neurodegenerative and gut-brain disorders like ALS, Parkinson’s, and Alzheimer’s. It uses cutting-edge AI, federated learning, and privacy-preserving frameworks to harmonize clinical, genomic, and environmental data.</div></p>

<p><div style='text-align: justify'>I started working in this project few months ago where the idea is to implement and fine-tuned transformer models like DNABERT, Nucleotide Transformer and HyenaDNA to process genomic sequences specific to ALS patients. Focused on discovering genetic patterns to aid in the identification of possible novel therapeutic targets. Collaborated on developing a self-supervised framework for processing unlabeled data, improving model performance on large-scale patient datasets like the AnswerALS dataset.</div></p>

---

HistoLung project as part of the ExaMode project
======

<div style='text-align: justify'>As part of my internship I was told to develop a model that should classify different cancer subtypes from digital pathology images. The <a href='https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12933/3006708/A-full-pipeline-to-analyze-lung-histopathology-images/10.1117/12.3006708.short'>results</a> of this project were accepted and presented at the SPIE Medical Imaging 2024 conference in San Diego (<a href='https://github.com/lluisb3/histo_lung'>GitHub repository</a>).</div>

<div style='text-align: center'><img src='/images/pipeline_hlung.png' alt="drawing" width="800"></div>

<p><div style='text-align: justify'>The figure above presents the Full Pipeline to train the lung cancer subtype classification model. A: Preprocessing of the Whole Slide Images (WSI) for patch extraction. B: Self-supervised learning to pre-train the feature extractor capturing high-level concepts directly from the histopathological lung patches using Momentum Contrastive Learning (MoCo v2). C: Training of a Multiple Instance Learning (MIL) model for the lung cancer classification task among, LUng ADenocarcinoma (LUAD), LUng Squamous cell Carcinoma (LUSC), Small-Cell Lung Cancer (SCLC), and NormaL tissue (NL), using a multi-label strategy.</div></p>

<p><div style='text-align: justify'>For qualitative evaluation of the MIL model performance, a heatmap is computed on the model with the best performance. The following figure shows that the model obtains a higher attention score in two of the three areas where the LUSC cancer is located as pointed out by the manual annotations from an expert pathologist.</div></p>

<div style='text-align: center'><img src='/images/heatmaps.png' alt="drawing" width="500"></div>

<div style='text-align: justify'>The Uniform Manifold Approximation and Projection (UMAP) is computed from the features extracted from the self-supervised model on 384 patches (135 cells, 158 glands, and 91 stroma) selected by an expert pathologist. Qualitatively, as shown in the next image the self-supervised model can almost perfectly cluster the three types of patches into clear separable regions.</div>
<div style='text-align: center'><img src='/images/umap_self-supervision.png'> </div>