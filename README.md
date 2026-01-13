# C2F-Fusion: Meta-learning Driven Coarse-to-Fine Cascade for Infrared and Visible Image Fusion

* * *

> **📢 Note**
> 
> This repository contains the supplementary material and code implementation for the paper "C2F-Fusion: Meta-learning Driven Coarse-to-Fine Cascade for Infrared and Visible Image Fusion".
> 
> The full source code and pretrained models will be made publicly available upon acceptance.

* * *

📖 Abstract

Infrared and visible image fusion aims to integrate complementary information from distinct modalities to enhance scene representation. Although deep learning-based methods have achieved significant progress, most existing approaches are constrained by a single-stage reconstruction paradigm. To address these challenges, we propose **C2F-Fusion**, a meta-learning-based network that establishes a multi-task framework via a coarse-to-fine cascade mechanism.

**Key Contributions:**

* **Coarse-to-Fine Cascade:** A progressive decomposition strategy that divides the fusion task into coarse perception and fine inference stages, utilizing a semantic mask for guidance.
  
* **HDDF Module:** A Hierarchy-aware Dual-Domain Fusion module. It uses wavelet domain spectral decoupling for shallow features and a semantic-guided bidirectional cross-attention mechanism for deep features.
  
* **TDMO Strategy:** A Task Decoupling Meta-Optimization strategy designed to address gradient dominance issues during multi-task joint training.
