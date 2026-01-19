# Machine Learning for Single Event Transient Detection

This repository contains the machine learning work for a Radiation Effects and Reliability course project focused on identifying and classifying Single Event Transients (SETs) in real radiation testing data.

## Repository Contents

### ClusteringMLClassification.ipynb
Primary notebook containing the full machine learning pipeline. This includes:
- Structuring raw radiation signal data into learning samples
- Feature extraction from time-series signals
- Unsupervised clustering using k-means to impose structure on unlabeled data
- Manual interpretation of clusters as transient or non-transient
- Classification using k-nearest neighbors (KNN)
- Qualitative evaluation through visual inspection and consistency across experiments

This notebook represents the core ML contribution of the project.

### ModeThresholding.ipynb
Implements a statistical thresholding baseline for transient detection. This method identifies candidate transients based on deviations from the signal distribution and serves as an interpretable reference point for evaluating the machine learning approach.

### Standardization.ipynb
An exploratory notebook used to test and validate feature scaling and normalization choices prior to clustering and classification. This work informed preprocessing decisions used in the main pipeline.

### TeyeWoodwardPoster.pptx
Final project poster summarizing the problem, methodology, and results.

### TeyeWoodwardReport.docx
Final written report describing the experimental setup, statistical baseline, machine learning approach, and evaluation in detail.

