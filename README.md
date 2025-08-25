# UDT: Unsupervised Discovery of Transformations between Fine-Grained Classes in Diffusion Models

This repository contains the project page for **UDT**, accepted at **BMVC 2025**.  

---

## 🔗 Project Page

The project page is implemented in static HTML/CSS/JS and can be deployed on GitHub Pages or any static web server.

- **Demo Website**: [URL OF THE WEBSITE](#)  
- **Paper (arXiv PDF)**: [Link](https://arxiv.org/pdf/<ARXIV PAPER ID>.pdf)  
- **Supplementary Material**: [PDF](static/pdfs/supplementary_material.pdf)  

---

## 📑 Abstract

Diffusion models demonstrate excellent performance in image generation and synthesis.  
Effective and controllable editing with these models requires a deep understanding of their latent spaces, a primary focus of prior research.  However, existing unsupervised exploration methods like NoiseCLR often remain at attribute-level edits, revealing limitations in complex fine-grained class transformations.  

To address this, we propose **UDT** (**U**nsupervised **D**iscovery of **T**ransformations), a novel framework that, while operating in a fully unsupervised setting, supports fine-grained class transformations by structuring the latent space in a hierarchy-aware manner.  

UDT leverages hierarchy-informed contrastive learning to disentangle class-defining traits using parent class guidance.  This systematic approach structures the latent space to support diverse and meaningful transformations while ensuring semantic consistency and pose preservation.  

Experiments on dog, cat, bird, and flower datasets demonstrate that **UDT** outperforms existing methods in generating coherent, diverse, and semantically accurate edits.  These results suggest **UDT** is a scalable and effective approach for semantic latent space exploration in diffusion models.

---

