---
title: "HistoLung project as part of the ExaMode project"
excerpt: "<div style='text-align: justify'> HistoLung to classify different lung cancer subtypes from digital biopsies (Whole Slide Images) using self-supervised learning and multiple instance learning.</div>"
collection: portfolio
---

<div style='text-align: justify'>As part of my internship I was told to develop a model to be able to classify different cancer subtypes from digital pathology images. The <a href='https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12933/3006708/A-full-pipeline-to-analyze-lung-histopathology-images/10.1117/12.3006708.short'>results</a> were accepted and presented at the SPIE Medical Imaging 2024 conference in San Diego. <a href='https://github.com/lluisb3/histo_lung'>GitHub to histo_lung</a></div>

<img src='/images/pipeline_hlung.png'>

<div style='text-align: justify'>The figure above presents the Full Pipeline to train the lung cancer subtype classification model. A: Preprocessing of the Whole Slide Images (WSI) for patch extraction. B: Self-supervised learning to pre-train the feature extractor capturing high-level concepts directly from the histopathological lung patches using Momentum Contrastive Learning (MoCo v2). C: Training of a Multiple Instance Learning (MIL) model for the lung cancer classification task among, LUng ADenocarcinoma (LUAD), LUng Squamous cell Carcinoma (LUSC), Small-Cell Lung Cancer (SCLC), and NormaL tissue (NL), using a multi-label strategy.<br>

For qualitative evaluation of the MIL model performance, a heatmap is computed on the model with the best performance. The following figure shows that the model obtains a higher attention score in two of the three areas where the LUSC cancer is located as pointed out by the manual annotations from an expert pathologist.</div>

<img src='/images/heatmaps.png'>

<div style='text-align: justify'>The Uniform Manifold Approximation and Projection (UMAP) is computed from the features extracted from the self-supervised model on 384 patches (135 cells, 158 glands, and 91 stroma) selected by an expert pathologist. Qualitatively, as shown in the next image the self-supervised model can almost perfectly cluster the three types of patches into clear separable regions.</div>
<div style='text-align: center'><img src='/images/umap_self-supervision.png'> </div>

