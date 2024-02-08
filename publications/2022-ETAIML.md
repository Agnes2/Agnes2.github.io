---
date: "2022-10-03"
description: Agnès Pérez Millan, Laia Borrell, José Contador, Mircea Balasa, Albert Lladó, Raquel Sanchez-Valle, Roser Sala-Llonch


featured: false
link: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12204/122040D/Classification-between-early-onset-Alzheimers-disease-and-frontotemporal-dementia-using/10.1117/12.2632990.short
pubtype: Proceeding
sitemap:
  priority: 0.8
tags:
- AD
- EOAD
- FTD
- Machine Learning
- SVM
- Longitudinal Study
- MRI
title: 'Classification between early onset Alzheimer´s disease and frontotemporal dementia using a single neuroimaging feature'
weight: 400
---

**Agnès Pérez Millan**, Laia Borrell, José Contador, Mircea Balasa, Albert Lladó, Raquel Sanchez-Valle, Roser Sala-Llonch. _Emerging Topics in Artificial Intelligence (ETAI) 2022_.

**ABSTRACT**

INTRODUCTION: Early Onset Alzheimer’s Disease (EOAD, <65 years) and Frontotemporal Dementia (FTD) are common forms of early-onset dementia. Therefore, there is a need to establish accurate diagnosis and to obtain markers for disease tracking. We combined supervised and unsupervised machine learning (ML) to discriminate between EOAD and FTD patients.

METHODS: We included 3T-T1 MRI of 203 subjects under 65 years old: 66 healthy controls (CTR, age: 55.0 ± 8.4 years), 85 EOAD patients (age: 57.3 ± 6.1 years) and 52 FTD patients (age: 57.9 ± 4.8 years). We obtained subcortical gray matter volumes and cortical thickness (CTh) regional measures using FreeSurfer. For ML, we performed a Principal Component Analysis (PCA) of all volumes and CTh values. Then, the first principal component (PC) was introduced into a Support Vector Machine (SVM). Overall performance was assessed using k-fold cross-validation.

RESULTS: Our algorithm had an accuracy of 87.2 ± 14.2 % in the CTR vs EOAD classification, 80.8 ± 20.4% for CTR vs FTD, 66.5 ± 12.9 % for EOAD vs FTD and 65.2 ± 10.6% when discriminating the three groups. We used the weights of the first PC to create disease-specific patterns.

CONCLUSION: By using a single feature that combines information from CTh and subcortical volumes, our algorithm classifies CTR, EOAD and FTD with good accuracy. We suggest that this approach can be used as a feature reduction strategy in ML algorithms while providing interpretable atrophy patterns.

