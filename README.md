# undergraduate-nonstationary-imbalanced-ml-thesis
This repository contains the code for my undergraduate thesis. The work focuses on machine learning problems where data is nonstationary and class distribution is imbalanced.
# A Diagnostic-Driven Framework for Hybrid ML in Nonstationary and Imbalanced Data

## Overview
This repository contains the code for my undergraduate thesis.
The work focuses on machine learning problems where data is
nonstationary and class distribution is imbalanced at the same time.

## Motivation
In real-world datasets, data distributions often change over time
and minority classes are underrepresented. Fixed machine learning
pipelines often fail under these conditions. This thesis proposes
a diagnostic-driven framework that selects hybrid learning strategies
based on data characteristics.

## Framework
The framework uses:
- Statistical diagnostics (ADF, KPSS)
- Imbalance diagnostics (minority rate, imbalance ratio)
- Model-based diagnostics

Based on these diagnostics, the system recommends:
- Resampling strategies
- Adaptive or static models
- Update strategies

## Experiments
- Synthetic datasets with controlled drift and imbalance
- Real-world datasets

The proposed approach is compared against fixed and ad-hoc pipelines.

## Results
Results show that the diagnostic-driven framework produces more
robust and stable performance under evolving and skewed data
distributions.

## Thesis
The thesis manuscript will be added after official approval.
