Thesis Title
A Diagnostic-Driven Framework for Selecting Hybrid ML Strategies in Nonstationary and Imbalanced Data
Author
Haris Md Sahed
Undergraduate Thesis
Department of Digital Business & Innovation
Tokyo International University
Supervisor
Prof. Fatih Ozaydin
Overview
This thesis studies how machine learning models behave when data has two common real-world problems: nonstationarity (data patterns change over time) and class imbalance (some classes appear much less than others). These issues often happen together and can reduce model performance if not handled properly.
Instead of using a fixed machine learning pipeline, this thesis proposes a diagnostic-driven framework. The idea is to first analyze the data using statistical and model-based diagnostics, and then select suitable hybrid strategies such as resampling, adaptive learning, or model updating based on those diagnostics.
The framework aims to help researchers and practitioners make better decisions when choosing machine learning strategies for changing and imbalanced data.
Objectives
Identify nonstationarity and class imbalance using statistical diagnostics
Measure imbalance severity and concept drift over time
Recommend suitable hybrid ML strategies based on diagnostic results
Compare diagnostic-driven pipelines with fixed and ad-hoc approaches
Evaluate performance on both synthetic and real-world datasets
Datasets
The experiments use multiple datasets with different characteristics, including:
Synthetic datasets with controlled drift and imbalance
Real-world datasets from domains such as healthcare, finance, and retail
Each dataset is analyzed independently to highlight how data characteristics influence model choice.
Methodology
Diagnostic Analysis
Stationarity tests (ADF, KPSS)
Class imbalance metrics
Drift indicators
Strategy Selection
Resampling techniques
Adaptive and incremental models
Model update strategies
Model Training & Evaluation
Traditional ML models (e.g., Random Forest, XGBoost)
Performance comparison using metrics suitable for imbalanced data
Results
The results show that:
Fixed pipelines often fail under changing and imbalanced conditions
Diagnostic-driven strategies adapt better to data changes
Hybrid approaches selected using diagnostics produce more stable and reliable predictions
