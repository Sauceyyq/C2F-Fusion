Towards High-Level Vision Tasks: A Texture-Semantic Collaborative Network for Infrared and Visible Image Fusion

* * *

> **📢 Note**
> 
> This repository contains the supplementary material and code implementation for the paper "Towards High-Level Vision Tasks: A Texture-Semantic Collaborative Network for Infrared and Visible Image Fusion".
> 
> The full source code and pretrained models will be made publicly available upon acceptance.

* * *
* * *
🧠 Architecture
<img width="7881" height="3288" alt="Work" src="https://github.com/user-attachments/assets/c7b93fb5-a6c1-4010-b09d-f5914dea67e7" /># 
* * *
📖 Abstract

Infrared and visible image fusion aims to integrate complementary information from distinct modalities to enhance scene representation. Although deep learning-based methods have achieved significant progress, most existing approaches are constrained by a single-stage reconstruction paradigm. To address these challenges, we propose **PRCFusion**, a fusion network that establishes a multi-task framework via a progressive refinement cascade mechanism.

**Key Contributions:**

* **Progressive Refinement Cascade Mechanism:** A progressive decomposition strategy that divides the fusion task into coarse perception and fine perception stages, utilizing a semantic mask for guidance.
  
* **HDDF Module:** A Hierarchy-aware Dual-Domain Fusion module. It uses wavelet domain spectral decoupling for shallow features and a semantic-guided bidirectional cross-attention mechanism for deep features.
  
* **TDMO Strategy:** A Task Decoupling Meta-Optimization strategy designed to address gradient dominance issues during multi-task joint training.
