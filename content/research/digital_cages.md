---
title: "🐁 Digital Cages Behavioral Data Analysis"
date: 2025-07-14
weight: 3
draft: false
description: "Statistical modeling and feature extraction for high-resolution mouse actigraphy data."
tags: ["statistical modeling", "time series", "feature extraction", "behavioral data"]
---

**Advisors (University of Michigan):**  
[Prof. Ivo D. Dinov](https://nursing.umich.edu/faculty-staff/faculty/ivo-d-dinov), [Dr. Simeone Marino](https://medschool.umich.edu/profile/2984/simeone-marino)

### **Overview**  
This project examines high-resolution actigraphy data from digitally monitored mice to characterize latent behavioral structure and identify informative temporal features. Rather than treating the dataset as a purely clustering problem, the analysis focuses on **feature engineering, dimensionality reduction, and temporal pattern extraction** to support downstream modeling of sleep–wake cycles and circadian stability.

### **Contributions**  
- Cleaned, aggregated, and reshaped raw actigraphy streams into analysis-ready time-series matrices  
- Performed feature extraction (activity bursts, rest intervals, circadian periodicity) to quantify behavioral variability  
- Applied PCA and sparse filtering to identify low-dimensional structure  
- Used clustering (k-means, hierarchical) to explore behavioral state patterns  
- Implemented the **NExOS** algorithm to identify **informative and sparse** behavioral features  
- Generated reproducible analysis pipelines in R and Python

### **Methods & Tools**  
- **Statistical methods:** PCA, feature selection, clustering, time-series decomposition  
- **Software:** R, Python  
- **Data:** high-frequency digital cage actigraphy (movement + temporal structure)
