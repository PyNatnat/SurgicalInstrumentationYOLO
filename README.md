# SurgicalInstrumentationYOLO
Repository for "Surgical Instrument Tracking: A Lightweight YOLO Approach Across Diverse Domains", submitted to ICCSA 2026. Contains codes and supplementary materials.

# Surgical Instrument Tracking: A Lightweight YOLO Approach Across Diverse Domains

[![Status: Accepted](https://img.shields.io/badge/Status-Accepted_at_ICCSA_2026-green.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()

> **🎉 Update:** This paper has been **Accepted** for presentation at the **International Conference on Computational Science and Its Applications (ICCSA 2026)** and for publication in the Springer LNCS Proceedings. We are currently finalizing the camera-ready version.

## 📌 Overview

Artificial intelligence has the potential to improve robotic and laparoscopic surgery through accurate surgical instrument tracking. Our work addresses the challenge of heterogeneous annotations and class imbalances by unifying three diverse surgical datasets (CholecTrack20, ROBUST-MIPS, and Badilla-Solórzano et al.).

Using a **lightweight YOLOv11-s** architecture, the model achieved a mean Average Precision (mAP@0.5) of **90.2%** and an inference speed of **5.1 ms per frame**, demonstrating viability for resource-constrained environments.

## Dataset and Supplementary Results

The complete unified dataset (images and YOLO labels) and the supplementary evaluation results (including PR curves and qualitative tracking figures) used in this research are publicly available on Zenodo: 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20173477.svg)](https://doi.org/10.5281/zenodo.20173477)
