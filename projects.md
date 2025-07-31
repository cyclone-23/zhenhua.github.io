---
layout: default
title: Projects
---

# AO-ICG Retinal Disease Classification

<img src="assets/img/ARVO_2025.png" width="1000">

**Authors**: Zhen Hua, Tao Liu, Joanne Li, Nancy Aguilera, Andrew J. Bower, Catherine A. Cukras, Robert B. Hufnagel, Emily Y. Chew, Brian P. Brooks, Wadih M. Zein, Laryssa A. Huryn, Johnny Tam  
**Presented at**: ARVO 2025, National Eye Institute, NIH

---

###  Purpose

Adaptive optics enhanced indocyanine green (AO-ICG) angiography enables high-resolution imaging of the choriocapillaris. This project introduces a feature engineering framework to quantitatively analyze microscopic changes in vascular structure in healthy vs. diseased eyes.

---

###  Methods

- **Imaging**: AO-ICG angiography with RPE-subtracted contrast
- **Subjects**: 36 participants (19 healthy, 17 diseased including AMD and genetic disorders)
- **Preprocessing**: Flow-void enhancement filtering
- **Analysis**:
  - Radially Averaged Power Spectrum (RAPS) for spatial frequency analysis
  - Extracted three interpretable features:
    - **Peak Location**: vessel spacing
    - **Peak Height**: pattern regularity
    - **Peak FWHM**: structural coherence
  - PCA and SHAP used to identify dominant features
  - Hierarchical clustering for unsupervised cohort separation

---

###  Results

- Clear visual contrast between healthy and diseased meshwork integrity
- **All three features** significantly differed between groups (p < 0.01)
- PCA and SHAP consistently ranked **peak location, FWHM, and height** as top discriminators
- **Unsupervised clustering** using only these features achieved:
  - **Accuracy: 83%**
  - **Sensitivity: 100%**

---

###  Significance

This project demonstrates that spatial frequency–based feature engineering can reveal subtle, disease-relevant changes in choriocapillaris architecture. The pipeline offers a quantitative, interpretable tool for understanding vascular degradation and holds potential for early diagnosis and disease monitoring in retinal pathologies.

---


