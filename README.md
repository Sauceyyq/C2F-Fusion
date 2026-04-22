<div align="center">

<h1>PRFusion: A Task-Driven Progressive Refinement Network for Infrared and Visible Image Fusion</h1>

<div>
    <a href="https://pytorch.org/"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" /></a>
    <a href="#"><img src="https://img.shields.io/badge/Paper-Coming_Soon-blue?style=for-the-badge&logo=arxiv&logoColor=white" alt="Paper" /></a>
</div>

<br>

**Official PyTorch implementation of PRFusion.**

</div>

> [!NOTE]  
> 
> 🚀 **The full source code, datasets, and pretrained models will be made publicly available upon acceptance.**

---

## 📖 Abstract

Infrared and visible image fusion integrates complementary multimodal features to preserve structural details and highlight salient targets, thereby facilitating downstream vision tasks. However, existing task-oriented methods face two major limitations: insufficient cross-modal complementary aggregation for key target regions, and gradient interference between tasks during joint optimization. To address these challenges, we propose PRFusion, a progressive refinement image fusion network collaborative with segmentation tasks, aimed at enhancing the depiction of key target regions and improving support for downstream perception.

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

---
