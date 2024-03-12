# Awesome Digital and Computational Pathology [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This curated list of useful resources is supported by:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://paige.ai/wp-content/uploads/2021/12/logo-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://paige.ai/wp-content/uploads/2021/12/logo-black.svg">
  <img alt="Paige AI" src="https://paige.ai/wp-content/uploads/2021/12/logo-black.svg" width="256">
</picture>

## Contents

- [Software](#software)
  - [Image Analysis](#image-analysis)
  - [Image IO](#image-io)
  - [Machine Learning](#machine-learning)
  - [Model](#model)
  - [Platform](#platform)
  - [Viewer](#viewer)
  - [Viewer (Free)](#viewer-free)
- [Data](#data)
  - [Challenges](#challenges)
  - [Datasets](#datasets)
  - [References](#references)
- [Publications](#publications)
  - [Papers](#papers)

## Software

### Image Analysis

- [HistomicsTK](https://github.com/DigitalSlideArchive/HistomicsTK/) - Toolkit for the analysis of digital pathology images.
- [HistoQC](https://github.com/choosehappy/HistoQC/) - Quality control tools for digital pathology.
- [TIA Toolbox](https://github.com/TissueImageAnalytics/tiatoolbox/) - Computational pathology toolbox that provides an end-to-end API for pathology image analysis.

### Image IO

- [Bio-Formats](https://github.com/ome/bioformats/) - Java software tool for reading and writing microscopy image using standardized, open formats.
- [cuCIM](https://github.com/rapidsai/cucim/) - NVIDIA's accelerated computer vision and image processing software library for multidimensional images.
- [libvips](https://www.libvips.org/) - A fast image processing library with low memory needs.
- [OpenSlide](https://openslide.org/) - Provides a simple C interface with Python bindings to read WSIs in multiple formats.

### Machine Learning

- [histocartography](https://github.com/BiomedSciAI/histocartography/) - Library designed to facilitate the development of graph-based computational pathology pipelines.
- [PathML](https://github.com/Dana-Farber-AIOS/pathml/) - Tools for computational pathology.
- [Slideflow](https://slideflow.dev/) - Python package that provides a unified API for building and testing deep learning models for histopathology.

### Model

- [Cell-DETR](https://github.com/ChristophReich1996/Cell-DETR/) - Attention-based transformers for instance segmentation of cells in microstructures.
- [CLAM](https://github.com/mahmoodlab/CLAM/) - Data-efficient and weakly supervised computational pathology on WSI.
- [DeepLIIF](https://github.com/nadeemlab/DeepLIIF/) - Deep-learning inferred multiplex immunofluorescence for immunohistochemical image quantification.
- [HIPT](https://github.com/mahmoodlab/HIPT/) - Scaling vision transformers to gigapixel images via hierarchical self-supervised learning.
- [HistoSegNet](https://github.com/lyndonchan/hsn_v1/) - Semantic segmentation of histological tissue type in WSIs.
- [HoVer-Net](https://github.com/vqdang/hover_net/) - Simultaneous segmentation and classification of nuclei in multi-tissue histology images.
- [MCAT](https://github.com/mahmoodlab/MCAT/) - Multimodal co-attention transformer for survival prediction in gigapixel WSIs.
- [Patch-GCN](https://github.com/mahmoodlab/Patch-GCN/) - WSI are 2D point clouds: Context-aware survival prediction using patch-based graph convolutional networks.
- [StainTools](https://github.com/Peter554/StainTools/) - Tools for tissue image stain normalisation and augmentation.
- [StarDist](https://github.com/stardist/stardist/) - Object detection with star-convex shapes.
- [TCGA segmentation](https://github.com/MarvinLer/tcga_segmentation/) - Weakly supervised multiple instance learning histopathological tumor segmentation.
- [torchstain](https://github.com/EIDOSLAB/torchstain/) - Stain normalization transformations.
- [TransMIL](https://github.com/szc19990412/TransMIL/) - Transformer based correlated multiple instance learning for WSI classification.
- [TransPath](https://github.com/Xiyue-Wang/TransPath/) - Transformer-based unsupervised contrastive learning for histopathological image classification.

### Platform

- [Digital Slide Archive](https://digitalslidearchive.github.io/digital_slide_archive/) - Provides the ability to store, manage, visualize and annotate large imaging datasets.

### Viewer

- [ASAP](https://computationalpathologygroup.github.io/ASAP/) - Desktop application for visualizing, annotating and automatically analyzing WSIs.
- [Cytomine](https://doc.cytomine.org/) - Collaborative analysis of WSIs.
- [HistomicsUI](https://github.com/DigitalSlideArchive/HistomicsUI/) - Web interface to visualize WSI and manage annotations.
- [QuickAnnotator](https://github.com/choosehappy/QuickAnnotator/) - Model assisted tool for rapid annotation of WSIs.
- [QuPath](https://qupath.github.io/) - Java application that enables researchers and pathologists to visualize, analyze and annotate WSIs.

### Viewer (Free)

- [Aperio ImageScope](https://www.leicabiosystems.com/en-ca/digital-pathology/manage/aperio-imagescope/) - Freely downloadable software for viewing WSIs. Windows only.

## Data

### Challenges

- [ACDC](https://acdc-lunghp.grand-challenge.org/) - Automatic Cancer Detection and Classification of lung histopathology.
- [ACROBAT](https://acrobat.grand-challenge.org/) - AutomatiC Registration Of Breast cAncer Tissue.
- [ANHIR](https://anhir.grand-challenge.org/) - Automatic Non-rigid Histological Image Registration.
- [BACH](https://iciar2018-challenge.grand-challenge.org/) - BreAst Cancer Histology images.
- [BCI](https://bci.grand-challenge.org/) - Breast Cancer Immunohistochemical image generation.
- [BreastPathQ](https://breastpathq.grand-challenge.org/) - Quantitative biomarkers for the determination of cancer cellularity.
- [CAMELYON16](https://camelyon16.grand-challenge.org/) - Cancer metastasis detection in lymph node.
- [CAMELYON17](https://camelyon17.grand-challenge.org/) - Building on CAMELYON16 by moving from slide level analysis to patient level analysis.
- [CellSeg](https://neurips22-cellseg.grand-challenge.org/) - Cell segmentation in multi-modality high-resolution microscopy images.
- [CoNIC](https://conic-challenge.grand-challenge.org/) - Colon Nuclei Identification and Counting.
- [DigestPath 2019](https://digestpath2019.grand-challenge.org/) - Digestive-system pathological detection and segmentation.
- [ENDO-AID](https://endo-aid.grand-challenge.org/) - Endometrial carcinoma detection in pipelle biopsies.
- [HER2 Scoring Contest](https://warwick.ac.uk/fac/cross_fac/tia/data/her2contest/) - Automated HER2 scoring algorithms in WSI of breast cancer tissues.
- [HEROHE](https://ecdp2020.grand-challenge.org/) - Predicting HER2 status in breast cancer from H&E.
- [LYSTO](https://lysto.grand-challenge.org/) - LYmphocytes aSsessment hackathOn in immunohistochemically stained tissue sections.
- [LYON19](https://lyon19.grand-challenge.org/) - LYmphocyte detectiON in IHC stained specimens.
- [MIDOG 2021](https://imig.science/midog2021/) - MItosis DOmain Generalization on tissue preparation and image acquisition.
- [MIDOG 2022](https://imig.science/midog/) - MItosis DOmain Generalization on tissue types.
- [MITOS-ATYPIA-14](https://mitos-atypia-14.grand-challenge.org/) - Detection of mitosis and evaluation of nuclear atypia score.
- [MoNuSAC](https://monusac-2020.grand-challenge.org/) - Multi-Organ NUclei Segmentation And Classification.
- [PAIP2019](https://paip2019.grand-challenge.org/) - Liver cancer segmentation.
- [PAIP2020](https://paip2020.grand-challenge.org/) - Classification and segmentation of microsatellite instability (MSI) in colorectal cancer.
- [PAIP2021](https://paip2021.grand-challenge.org/) - Perineural invasion in multiple organ cancer.
- [PAIP2023](https://2023paip.grand-challenge.org/) - Tumor cellularity prediction in pancreatic cancer and colon cancer.
- [PANDA](https://www.kaggle.com/competitions/prostate-cancer-grade-assessment/) - Prostate cANcer graDe Assessment.
- [SegPC](https://segpc-2021.grand-challenge.org/) - Segmentation of multiple myeloma in Plasma Cells.
- [TUPAC16](https://tupac.grand-challenge.org/) - TUmor Proliferation Assessment.
- [WSSS4LUAD](https://wsss4luad.grand-challenge.org/) - Weakly-supervised tissue semantic segmentation for lung adenocarcinoma.

### Datasets

- [ARCH](https://warwick.ac.uk/fac/cross_fac/tia/data/arch/) - Multiple instance captioning.
- [BCNB](https://bcnb.grand-challenge.org/) - Early Breast Cancer Core-Needle Biopsy WSI dataset.
- [BCSS](https://bcsegmentation.grand-challenge.org/) - Breast Cancer Semantic Segmentation.
- [BRACS](https://www.bracs.icar.cnr.it/) - BReAst Carcinoma Subtyping.
- [CRC](https://zenodo.org/record/1214456/) - 100,000 histological images of human colorectal cancer and healthy tissue.
- [MHIST](https://bmirds.github.io/MHIST/) - Minimalist histopathology image analysis dataset.
- [NuCLS](https://sites.google.com/view/nucls/home/) - A scalable crowdsourcing approach & dataset for nucleus classification, localization and segmentation in breast cancer.
- [PCAM](https://github.com/basveeling/pcam/) - PatchCamelyon provides a new benchmark for machine learning models akin to CIFAR-10 and MNIST.
- [TCGA](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/) - The Cancer Genome Atlas is a landmark cancer genomics program that molecularly characterized over 20,000 primary cancer and matched normal samples spanning 33 cancer types.
- [UNITOPATHO](https://github.com/EIDOSLAB/UNITOPATHO/) - A labeled histopathological dataset for colorectal polyps classification and adenoma dysplasia grading.
- [UNMaSk](https://github.com/pathdata/UNMaSk/) - Unmasking the immune microecology of ductal carcinoma in situ.

### References

- [WebPathology](https://www.webpathology.com/) - Visual survey of surgical pathology.

## Publications

### Papers

- [chen2022self](https://github.com/Richarizardd/Self-Supervised-ViT-Path/) - Self-Supervised Vision Transformers Learn Visual Concepts in Histopathology.
