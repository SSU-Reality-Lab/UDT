# UDT: Unsupervised Discovery of Transformations between Fine-Grained Classes in Diffusion Models

This repository contains the project page for **UDT**, accepted at **BMVC 2025**.  

---

## 🔗 Project Page

The project page is implemented in static HTML/CSS/JS and can be deployed on GitHub Pages or any static web server.

- **Project Website**: [https://ssu-reality-lab.github.io/UDT/](#)  
- **Paper (arXiv PDF)**: [PDF](static/pdfs/UDT_BMVC_2025.pdf) 
- **Supplementary Material**: [PDF](static/pdfs/UDT_BMVC_2025_SUPP.pdf)  

---

## 📑 Abstract
Diffusion models achieve impressive image synthesis, yet unsupervised methods for latent space exploration remain limited in fine-grained class translation. Existing approaches struggle with fine-grained class translation, often producing low-diversity outputs within parent classes or inconsistent child-class mappings across images.  We propose `UDT` (**U**nsupervised **D**iscovery of **T**ransformations), a framework that incorporates hierarchical structure into unsupervised direction discovery. `UDT` leverages parent-class prompts to decompose predicted noise into class-general and class-specific components, ensuring translations remain within the parent domain while enabling disentangled child-class transformations. A hierarchy-aware contrastive loss further enforces consistency, with each direction corresponding to a distinct child class. Experiments on dogs, cats, birds, and flowers show that `UDT` outperforms state-of-the-art methods both qualitatively and quantitatively.  Moreover, `UDT` supports controllable interpolation, allowing for the smooth generation of intermediate classes (*e.g.*, mixed breeds). These results demonstrate `UDT` as a general and effective solution for fine-grained image translation. 

---

