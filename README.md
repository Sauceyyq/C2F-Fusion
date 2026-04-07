<div align="center">

<h1>Towards High-Level Vision Tasks: A Texture-Semantic Collaborative Network for Infrared and Visible Image Fusion</h1>

<div>
    <a href="https://pytorch.org/"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" /></a>
    <a href="#"><img src="https://img.shields.io/badge/Paper-Coming_Soon-blue?style=for-the-badge&logo=arxiv&logoColor=white" alt="Paper" /></a>
    <a href="#"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" /></a>
</div>

<br>

**Official PyTorch implementation of PRCFusion.**

</div>

> [!NOTE]  
> 
> 🚀 **The full source code, datasets, and pretrained models will be made publicly available upon acceptance.**

---

## 📖 Abstract

Infrared and visible image fusion aims to integrate complementary information from distinct modalities to enhance scene representation. Although deep learning-based methods have achieved significant progress, most existing approaches are constrained by a single-stage reconstruction paradigm. 

To address these challenges, we propose **PRCFusion**, a fusion network that establishes a multi-task framework via a progressive refinement cascade mechanism.

### ✨ Key Contributions

- 🔄 **Progressive Refinement Cascade Mechanism:** A progressive decomposition strategy that divides the fusion task into *coarse perception* and *fine perception* stages, utilizing a semantic mask for guidance.
- 🧩 **HDDF Module (Hierarchy-aware Dual-Domain Fusion):** Utilizes wavelet domain spectral decoupling for shallow features and a semantic-guided bidirectional cross-attention mechanism for deep features.
- ⚖️ **TDMO Strategy (Task Decoupling Meta-Optimization):** A strategy specifically designed to address gradient dominance issues during multi-task joint training.

---

## 🧠 Architecture

<p align="center">
  <img width="95%" alt="Architecture of PRCFusion" src="https://github.com/user-attachments/assets/c7b93fb5-a6c1-4010-b09d-f5914dea67e7" />
</p>
<p align="center">
  <em>Figure 1: The overall architecture of the proposed PRCFusion network.</em>
</p>

---

## 🚀 Getting Started (Coming Soon)

Instructions for environment setup, dataset preparation, and evaluation will be updated here.

- [ ] Release inference code and pre-trained models.
- [ ] Release training code.

---
