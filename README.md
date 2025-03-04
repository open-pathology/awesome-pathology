# Awesome Digital and Computational Pathology [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This curated list of useful resources is supported by:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://paige.ai/wp-content/uploads/2021/12/logo-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://paige.ai/wp-content/uploads/2021/12/logo-black.svg">
  <img alt="Paige AI" src="https://paige.ai/wp-content/uploads/2021/12/logo-black.svg" width="256">
</picture>

## Contents

- [Software](#software)
  - [Assistant](#assistant) 
  - [Image Analysis](#image-analysis)
  - [Image IO](#image-io)
  - [Machine Learning](#machine-learning)
  - [Model](#model)
  - [Foundation Model](#foundation-model)
  - [Platform](#platform)
  - [Viewer](#viewer)
  - [Viewer (Free)](#viewer-free)
- [Data](#data)
  - [Challenges](#challenges)
  - [Datasets](#datasets)
  - [References](#references)
- [Publications](#publications)
  - [Papers](#papers)
  - [Repositories](#repositories)

## Software

### Assistant

- [Digital Pathology Assistant](https://chatgpt.com/g/g-L1IbnIIVt-digital-pathology-assistant-v3-0) - Specify your requirements in plain english and I'll provide PathML and Python code for your use-case.

### Image Analysis

- [CellPilot](https://github.com/philippendres/CellPilot/) - A unified approach to automatic and interactive segmentation in histopathology.
- [GrandQC](https://github.com/cpath-ukk/grandqc/) - A comprehensive solution to quality control problem in digital pathology.
- [HistomicsTK](https://github.com/DigitalSlideArchive/HistomicsTK/) - Toolkit for the analysis of digital pathology images.
- [HistoQC](https://github.com/choosehappy/HistoQC/) - Quality control tools for digital pathology.
- [InstanSeg](https://github.com/instanseg/instanseg/) - Cell and nucleus segmentation pipeline for fluorescence and brightfield microscopy images.
- [PatchSorter](https://github.com/choosehappy/PatchSorter/) - A tool for rapidly labeling objects using deep learning feature embedding.
- [PathProfiler](https://github.com/MaryamHaghighat/PathProfiler/) - Quality assessment of histopathology WSI cohorts.
- [PyHIST](https://github.com/manuel-munoz-aguirre/PyHIST/) - Histological image segmentation tool.
- [pyslide](https://github.com/PingjunChen/pyslide/) - Digital pathology WSI analysis toolbox.
- [TIA Toolbox](https://github.com/TissueImageAnalytics/tiatoolbox/) - Computational pathology toolbox that provides an end-to-end API for pathology image analysis.

### Image IO

- [Bio-Formats](https://github.com/ome/bioformats/) - Java software tool for reading and writing microscopy image using standardized, open formats.
- [compay-syntax](https://github.com/jgamper/compay-syntax/) - Tissue mask and tiling pipeline.
- [cuCIM](https://github.com/rapidsai/cucim/) - NVIDIA's accelerated computer vision and image processing software library for multidimensional images.
- [libvips](https://www.libvips.org/) - A fast image processing library with low memory needs.
- [NGFF-Converter](https://github.com/glencoesoftware/NGFF-Converter/) - GUI application for conversion of bioimage formats into OME-NGFF or OME-TIFF.
- [OpenSlide](https://openslide.org/) - Provides a simple C interface with Python bindings to read WSIs in multiple formats.
- [svg2svs](https://github.com/Ellogon/svg2svs/) - Generate checkerboard and build multi-layer pyramidal SVS files from SVG images.
- [tifffile](https://github.com/cgohlke/tifffile/) - Read and write TIFF-like files using in bioimaging.
- [WholeSlideData](https://github.com/DIAGNijmegen/pathology-whole-slide-data/) - Batch iterator that enables fast, efficient and easy patch sampling.

### Machine Learning

- [DLUP](https://github.com/nki-ai/dlup/) - Deep learning utilities for pathology.
- [ENACT](https://github.com/Sanofi-Public/enact-pipeline/) - End-to-end analysis and cell type annotation for Visium HD slides.
- [eva](https://github.com/kaiko-ai/eva/) - Evaluation framework for oncology foundation models.
- [histocartography](https://github.com/BiomedSciAI/histocartography/) - Library designed to facilitate the development of graph-based computational pathology pipelines.
- [MHIM-MIL](https://github.com/DearCaat/MHIM-MIL/) - Multiple instance learning framework with masked hard instance mining for WSI classification.
- [nuclei.io](https://github.com/huangzhii/nuclei.io/) - Human-in-the-loop active learning framework for pathology image analysis.
- [PathML](https://github.com/Dana-Farber-AIOS/pathml/) - Tools for computational pathology.
- [Slideflow](https://slideflow.dev/) - Python package that provides a unified API for building and testing deep learning models for histopathology.

### Model

- [ACMIL](https://github.com/dazhangyu123/ACMIL/) - WSI classification.
- [BEPH](https://github.com/Zhcyoung/BEPH/) - BEiT-based model pre-training on WSIs.
- [Cell-DETR](https://github.com/ChristophReich1996/Cell-DETR/) - Attention-based transformers for instance segmentation of cells in microstructures.
- [CellViT](https://github.com/TIO-IKIM/CellViT/) - Vision transformers for precise cell segmentation and classification.
- [Cerberus](https://github.com/TissueImageAnalytics/cerberus/) - Multi-task learning enables simultaneous histology image segmentation and classification.
- [CLAM](https://github.com/mahmoodlab/CLAM/) - Data-efficient and weakly supervised computational pathology on WSI.
- [DeepLIIF](https://github.com/nadeemlab/DeepLIIF/) - Deep-learning inferred multiplex immunofluorescence for immunohistochemical image quantification.
- [DiffInfinite](https://github.com/marcoaversa/diffinfinite/) - Large mask-image synthesis via parallel random patch diffusion in histopathology.
- [DMMN](https://github.com/MSKCC-Computational-Pathology/DMMN/) - Deep Multi-Magnification Network for multi-class tissue segmentation of WSI.
- [DT-MIL](https://github.com/yfzon/DT-MIL/) - Deformable transformer for multi-instance learning on histopathological image.
- [FrOoDo](https://github.com/MECLabTUDA/FrOoDo/) - Framework for out of distribution detection.
- [fseg](https://github.com/deepathology/fseg/) - Unsupervised semantic segmentation for pathology by factorizing foundation model features.
- [HistoGPT](https://github.com/marrlab/HistoGPT/) - Generating highly accurate histopathology reports from whole slide images.
- [HistoSegNet](https://github.com/lyndonchan/hsn_v1/) - Semantic segmentation of histological tissue type in WSIs.
- [HMIL](https://github.com/ChengJin-git/HMIL/) - Hierarchical multi-instance learning for fine-grained WSI classification.
- [HoVer-Net](https://github.com/vqdang/hover_net/) - Simultaneous segmentation and classification of nuclei in multi-tissue histology images.
- [LongViT](https://github.com/microsoft/torchscale/blob/main/examples/longvit/) - Vision Transformer that can process gigapixel images in an end-to-end manner.
- [MCAT](https://github.com/mahmoodlab/MCAT/) - Multimodal co-attention transformer for survival prediction in gigapixel WSIs.
- [MMP](https://github.com/mahmoodlab/MMP/) - Multimodal prototyping for cancer survival prediction.
- [MSINet](https://github.com/rikiyay/MSINet/) - Deep learning model for the prediction of microsatellite instability in colorectal cancer.
- [PANTHER](https://github.com/mahmoodlab/Panther/) - Morphological prototyping for unsupervised slide representation learning in computational pathology.
- [Patch-GCN](https://github.com/mahmoodlab/Patch-GCN/) - WSI are 2D point clouds: Context-aware survival prediction using patch-based graph convolutional networks.
- [RSP](https://github.com/srinidhiPY/SSL_CR_Histo/) - Self-supervised driven consistency training for annotation efficient histopathology image analysis.
- [Snuffy](https://github.com/jafarinia/snuffy/) - Efficient WSI classifier.
- [SparseConvMIL](https://github.com/MarvinLer/SparseConvMIL/) - Sparse convolutional context-aware multiple instance learning for WSI classification.
- [StainGAN](https://github.com/xtarx/StainGAN/) - Stain style transfer for digital histological images.
- [stainlib](https://github.com/sebastianffx/stainlib/) - Augmentation & normalization of H&E images.
- [StainTools](https://github.com/Peter554/StainTools/) - Tools for tissue image stain normalisation and augmentation.
- [StarDist](https://github.com/stardist/stardist/) - Object detection with star-convex shapes.
- [TANGLE](https://github.com/mahmoodlab/TANGLE/) - Transcriptomics-guided slide representation learning in computational pathology.
- [TCGA segmentation](https://github.com/MarvinLer/tcga_segmentation/) - Weakly supervised multiple instance learning histopathological tumor segmentation.
- [torchstain](https://github.com/EIDOSLAB/torchstain/) - Stain normalization transformations.
- [TransMIL](https://github.com/szc19990412/TransMIL/) - Transformer based correlated multiple instance learning for WSI classification.

### Foundation Model

- [BiomedCLIP](https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224/) - Multimodal biomedical foundation model pretrained from fifteen million scientific image-text pairs.
- [CONCH](https://github.com/mahmoodlab/CONCH/) - Vision-language foundation model for computational pathology.
- [Hibou](https://github.com/HistAI/hibou/) - A family of foundational vision transformers for pathology.
- [HIPT](https://github.com/mahmoodlab/HIPT/) - Scaling vision transformers to gigapixel images via hierarchical self-supervised learning.
- [H-optimus](https://github.com/bioptimus/releases/tree/main/models/h-optimus/v0/) - Foundation model for histology.
- [KEEP](https://github.com/MAGIC-AI4Med/KEEP/) - A Knowledge-enhanced pathology vision-language foundation model for cancer diagnosis.
- [MUSK](https://github.com/lilab-stanford/MUSK/) - A vision-language foundation model for precision oncology.
- [PathDino](https://kimialabmayo.github.io/PathDino-Page/) - Rotation-agnostic image representation learning for digital pathology.
- [Path Foundation](https://huggingface.co/google/path-foundation/) - Embedding model for efficiently building AI for histopathology applications.
- [PathoDuet](https://github.com/openmedlab/PathoDuet/) - Foundation models for pathological slide analysis of H&E and IHC stains.
- [Phikon](https://github.com/owkin/HistoSSLscaling/) - Scaling self-supervised learning for histopathology with masked image modeling.
- [Prov-GigaPath](https://github.com/prov-gigapath/prov-gigapath/) - A whole-slide foundation model for digital pathology from real-world data.
- [ROAM](https://github.com/whiteyunjie/ROAM/) - A transformer-based weakly supervised computational pathology method for clinical-grade diagnosis and molecular state revelation of gliomas.
- [TITAN](https://github.com/mahmoodlab/TITAN/) - Multimodal whole slide foundation model for pathology.
- [TransPath](https://github.com/Xiyue-Wang/TransPath/) - Transformer-based unsupervised contrastive learning for histopathological image classification.
- [UNI](https://github.com/mahmoodlab/UNI/) - General-purpose foundation model for computational pathology.
- [UNI2-h](https://huggingface.co/MahmoodLab/UNI2-h/) - General-purpose foundation model for computational pathology.
- [VIM4Path](https://github.com/AtlasAnalyticsLab/Vim4Path/) - Self-supervised vision mamba for WSIs.
- [Virchow](https://huggingface.co/paige-ai/Virchow/) - Self-supervised vision transformer pretrained using 1.5M WSIs.

### Platform

- [Digital Slide Archive](https://digitalslidearchive.github.io/digital_slide_archive/) - Provides the ability to store, manage, visualize and annotate large imaging datasets.

### Viewer

- [ASAP](https://computationalpathologygroup.github.io/ASAP/) - Desktop application for visualizing, annotating and automatically analyzing WSIs.
- [Cytomine](https://doc.cytomine.org/) - Collaborative analysis of WSIs.
- [DigiPathAI](https://github.com/haranrk/DigiPathAI/) - Tool to visualize gigantic pathology images and use AI to segment cancer cells and present as an overlay.
- [HistomicsUI](https://github.com/DigitalSlideArchive/HistomicsUI/) - Web interface to visualize WSI and manage annotations.
- [slim](https://github.com/ImagingDataCommons/slim/) - Interoperable web-based slide microscopy viewer and annotation tool.
- [QuickAnnotator](https://github.com/choosehappy/QuickAnnotator/) - Model assisted tool for rapid annotation of WSIs.
- [QuPath](https://qupath.github.io/) - Java application that enables researchers and pathologists to visualize, analyze and annotate WSIs.

### Viewer (Free)

- [Aperio ImageScope](https://www.leicabiosystems.com/en-ca/digital-pathology/manage/aperio-imagescope/) - Freely downloadable software for viewing WSIs. Windows only.
- [PathPresenter](https://www.pathpresenter.com/) - A complete enterprise workflow platform built by pathologists.

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
- [Gleason 2019](https://gleason2019.grand-challenge.org/) - Automatic Gleason grading of prostate cancer in digital histopathology.
- [HER2 Scoring Contest](https://warwick.ac.uk/fac/cross_fac/tia/data/her2contest/) - Automated HER2 scoring algorithms in WSI of breast cancer tissues.
- [HEROHE](https://ecdp2020.grand-challenge.org/) - Predicting HER2 status in breast cancer from H&E.
- [KPIs](https://sites.google.com/view/kpis2024/) - Kidney Pathology Image segmentation.
- [LEOPARD](https://leopard.grand-challenge.org/leopard/) - LEarning biOchemical Prostate cAncer Recurrence from histopathology sliDes.
- [LYSTO](https://lysto.grand-challenge.org/) - LYmphocytes aSsessment hackathOn in immunohistochemically stained tissue sections.
- [LYON19](https://lyon19.grand-challenge.org/) - LYmphocyte detectiON in IHC stained specimens.
- [MIDOG 2021](https://imig.science/midog2021/) - MItosis DOmain Generalization on tissue preparation and image acquisition.
- [MIDOG 2022](https://imig.science/midog/) - MItosis DOmain Generalization on tissue types.
- [MITOS-ATYPIA-14](https://mitos-atypia-14.grand-challenge.org/) - Detection of mitosis and evaluation of nuclear atypia score.
- [MONKEY](https://monkey.grand-challenge.org/) - Machine-learning for Optimal detection of iNflammatory cells in the KidnEY.
- [MoNuSAC](https://monusac-2020.grand-challenge.org/) - Multi-Organ NUclei Segmentation And Classification.
- [MoNuSeg](https://monuseg.grand-challenge.org/) - Multi-Organ NUclei Segmentation.
- [PAIP2019](https://paip2019.grand-challenge.org/) - Liver cancer segmentation.
- [PAIP2020](https://paip2020.grand-challenge.org/) - Classification and segmentation of microsatellite instability (MSI) in colorectal cancer.
- [PAIP2021](https://paip2021.grand-challenge.org/) - Perineural invasion in multiple organ cancer.
- [PAIP2023](https://2023paip.grand-challenge.org/) - Tumor cellularity prediction in pancreatic cancer and colon cancer.
- [PANDA](https://www.kaggle.com/competitions/prostate-cancer-grade-assessment/) - Prostate cANcer graDe Assessment.
- [SegPC](https://segpc-2021.grand-challenge.org/) - Segmentation of multiple myeloma in Plasma Cells.
- [TIGER](https://tiger.grand-challenge.org/) - Fully automated assessment of tumor-infiltrating lymphocytes (TILs) in H&E breast cancer slides.
- [TUPAC16](https://tupac.grand-challenge.org/) - TUmor Proliferation Assessment.
- [WSSS4LUAD](https://wsss4luad.grand-challenge.org/) - Weakly-supervised tissue semantic segmentation for lung adenocarcinoma.

### Datasets

- [ARCH](https://warwick.ac.uk/fac/cross_fac/tia/data/arch/) - Multiple instance captioning.
- [BCNB](https://bcnb.grand-challenge.org/) - Early Breast Cancer Core-Needle Biopsy WSI dataset.
- [BCSS](https://bcsegmentation.grand-challenge.org/) - Breast Cancer Semantic Segmentation.
- [BRACS](https://www.bracs.icar.cnr.it/) - BReAst Carcinoma Subtyping.
- [CATCH](https://www.cancerimagingarchive.net/collection/catch/) - CAnine cuTaneous Cancer Histology dataset.
- [CRC](https://zenodo.org/record/1214456/) - 100,000 histological images of human colorectal cancer and healthy tissue.
- [CryoNuSeg](https://github.com/masih4/CryoNuSeg/) - Nuclei segmentation of cryosectioned H&E-stained histological images.
- [H2T](https://github.com/vqdang/H2T/) - Handcrafted Histological Transformer for unsupervised representation of WSIs.
- [HEST](https://github.com/mahmoodlab/hest/) - Bringing spatial transcriptomics and histopathology together.
- [LC25000](https://github.com/tampapath/lung_colon_image_set/) - Lung and colon cancer histopathological image dataset.
- [LyNSeC](https://zenodo.org/records/8065174/) - Lymphoma nuclear segmentation and classification dataset.
- [MHIST](https://bmirds.github.io/MHIST/) - Minimalist histopathology image analysis dataset.
- [MS-SCC](https://github.com/DeepMicroscopy/MultiScanner_SCC/) - Multi-scanner squamous cell carcinoma dataset.
- [NuInsSeg](https://www.kaggle.com/datasets/ipateam/nuinsseg/) - A fully annotated dataset for nuclei instance segmentation in H&E-stained histological images.
- [NuCLS](https://sites.google.com/view/nucls/home/) - A scalable crowdsourcing approach & dataset for nucleus classification, localization and segmentation in breast cancer.
- [OCELOT](https://lunit-io.github.io/research/publications/ocelot/) - Overlapped cell on tissue dataset for histopathology.
- [OBR](https://www.cancerimagingarchive.net/collection/ovarian-bevacizumab-response/) - Ovarian Bevacizumab Response: a dataset of histopathological WSIs for classification of treatment effectiveness to ovarian cancer.
- [PanNuke](https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke/) - Dataset for nuclei instance segmentation and classification.
- [PCAM](https://github.com/basveeling/pcam/) - PatchCamelyon provides a new benchmark for machine learning models akin to CIFAR-10 and MNIST.
- [TCGA](https://www.cancer.gov/ccg/research/genome-sequencing/tcga/) - The Cancer Genome Atlas is a landmark cancer genomics program that molecularly characterized over 20,000 primary cancer and matched normal samples spanning 33 cancer types.
- [UNITOPATHO](https://github.com/EIDOSLAB/UNITOPATHO/) - A labeled histopathological dataset for colorectal polyps classification and adenoma dysplasia grading.
- [UNMaSk](https://github.com/pathdata/UNMaSk/) - Unmasking the immune microecology of ductal carcinoma in situ.

### References

- [ADP](https://github.com/mahdihosseini/ADP/) - Atlas of digital pathology for deep learning.
- [Cytomine Collection](https://cytomine.com/collection/) - Open access to high quality WSI in several formats.
- [DICOM WSI Standard](https://dicom.nema.org/dicom/dicomwsi/) - DICOM WSI document.
- [Jerad Gardner, MD](https://www.youtube.com/@JMGardnerMD/) - Popular YouTube channel for educational videos by a pathologist.
- [WebPathology](https://www.webpathology.com/) - Visual survey of surgical pathology.

## Publications

### Papers

- [chen2022self](https://github.com/Richarizardd/Self-Supervised-ViT-Path/) - Self-Supervised Vision Transformers Learn Visual Concepts in Histopathology.
- [kang2022benchmarking](https://lunit-io.github.io/research/publications/pathology_ssl/) - Benchmarking Self-Supervised Learning on Diverse Pathology Datasets.
- [wolflein2023good](https://github.com/georg-wolflein/good-features/) - A Good Feature Extractor Is All You Need for Weakly Supervised Pathology Slide Classification.
- [vaidya2024demographic](https://github.com/mahmoodlab/CPATH_demographics/) - Demographic bias in misdiagnosis by computational pathology models.
- [breen2024ovarian](https://github.com/scjjb/Ovarian_Features/) - Histopathology foundation models enable accurate ovarian cancer subtype classification.
- [matous2024latent](https://github.com/MatousE/rot-invariance-analysis/) - Are the latent representations of foundation models for pathology invarient to rotation?

### Repositories

- [stettler2022datasets](https://github.com/maduc7/Histopathology-Datasets/) - Resources of histopathology datasets.
- [jahanifar2023domain](https://github.com/mostafajahanifar/awesome-dg-cpath/) - Awesome domain generalization for computational pathology.
