# Left Atrial Segmentation from LGE-MRI
### B.Tech Final Year Project — D. Y. Patil International University, Pune

![Python](https://img.shields.io/badge/Python-3.8-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

## Overview
Comparative deep learning study for automated left atrial 
segmentation from Late Gadolinium-Enhanced MRI (LGE-MRI) 
cardiac scans. Three architectures were implemented, trained, 
and benchmarked against the Antonelli et al. (2022) 
state-of-the-art published result.

---

## Results

| Model | Mean DSC | Median DSC |
|---|---|---|
| 2D U-Net | 0.9278 | — |
| Custom 3D U-Net | 0.9009 | — |
| Enhanced nnU-Net | **0.9266** | **0.9318** |
| Antonelli et al. 2022 *(benchmark)* | 0.9250 | — |

> ✅ Enhanced nnU-Net exceeded the published benchmark (DSC 0.9250)
> running on constrained hardware — NVIDIA RTX 4060, 8GB VRAM.

---

## Dataset
- **Name:** Medical Segmentation Decathlon (MSD) — Task02: Heart
- **Modality:** Late Gadolinium-Enhanced MRI (LGE-MRI)
- **Size:** 20 volumetric 3D scans with ground truth segmentation masks
- **Link:** http://medicaldecathlon.com

---

## Setup & Usage

### 1. Clone the repository
```bash
git clone https://github.com/madhura-g-jadhav/left-atrial-segmentation-msd-task02.git
cd left-atrial-segmentation-msd-task02
```

### 2. Create environment
```bash
conda env create -f nnunet_env_windows.yml
conda activate nnunet_env
```

### 3. Run notebooks in order

---

## Hardware & Software
| Component | Details |
|---|---|
| GPU | NVIDIA RTX 4060 (8GB VRAM) |
| OS | Windows 10 |
| Python | 3.8 |
| PyTorch | 2.1.0 |
| PyTorch Lightning | 1.9.5 |

---

## Publication
> M. G. Jadhav et al.,
> *"Comparative Analysis of 2D U-Net, 3D U-Net, and Enhanced
> nnU-Net for Left Atrial Segmentation from LGE-MRI,"*
> Submitted to **CVMI 2026 (IEEE Conference)** — Under Review.

---

## Supervisors
**Mr. Prabir Kumar Das** | **Dr. Debashish Nath**
D. Y. Patil International University, Akurdi, Pune

---

## Contact
**Madhura Ganesh Jadhav**
📧 jadhavmadhura2705@gmail.com
🔗 github.com/madhura-g-jadhav
---

## Repository Structure
