# Predicting Long Non-coding RNA-Protein Interactions Based on Deep Learning Model

## Overview

This repository contains the research work and associated materials for the undergraduate thesis titled **"Predicting Long Non-coding RNA-Protein Interactions Based on Deep Learning Model"** submitted by Qin Su at Nankai University in May 2022. The thesis presents a novel deep learning approach using Graph Autoencoder (GAE) and Graph Attention Networks (GAT) to predict interactions between long non-coding RNAs (lncRNAs) and proteins, which are crucial for understanding complex biological processes and diseases.

## Table of Contents

- [Overview](#overview)
- [Thesis Structure](#thesis-structure)
- [Abstract](#abstract)
- [Research Background](#research-background)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)
- [References](#references)

## Thesis Structure

The thesis is structured as follows:

1. **Introduction**: Overview of lncRNA-protein interactions and the significance of predicting these interactions.
2. **Current Research Status**: Review of existing methods, including machine learning, network-based, and deep learning approaches.
3. **Methodology**: Detailed description of the Graph Autoencoder (GAE) and Graph Attention Networks (GAT) models used for predicting lncRNA-protein interactions.
4. **Experiment**: Parameter tuning, model optimization, and comparative experiments with other methods.
5. **Conclusion and Future Work**: Summary of findings and proposed directions for future research.

## Abstract

Long non-coding RNA (lncRNA) refers to RNA molecules longer than 200 nucleotides that do not encode proteins but play crucial roles in regulating various biological processes. The interactions between lncRNAs and proteins are vital for understanding cellular mechanisms and are closely associated with many human diseases. This thesis introduces a deep learning model based on Graph Autoencoder (GAE) and Graph Attention Networks (GAT) to predict lncRNA-protein interactions. The proposed model improves the accuracy of predictions through parameter optimization and collaborative training. Comparative experiments demonstrate the model's superiority over existing methods.

## Research Background

- **Long Non-coding RNA (lncRNA)**: Previously considered as "junk sequences," lncRNAs have been found to be involved in regulating key biological processes and are linked to various diseases.
- **Proteins**: Essential biopolymers involved in almost all biochemical reactions in cells. Interactions between lncRNAs and proteins are crucial for the biological functions of lncRNAs.
- **Significance of Predicting lncRNA-Protein Interactions**: Identifying these interactions helps in understanding disease mechanisms at the molecular level. Experimental methods for detecting these interactions are time-consuming and costly, making computational predictions a valuable alternative.

## Methodology

### Graph Autoencoder (GAE)
- **Graph Convolutional Neural Networks (GCN)**: Used as the core of the GAE to extract features from lncRNA and protein graphs and predict their interactions.
- **Collaborative Training**: A novel approach combining two GAEs trained on lncRNA and protein graphs, respectively, to enhance prediction accuracy.

### Graph Attention Networks (GAT)
- **Attention Mechanism**: Improves the model's ability to integrate vertex feature correlations, leading to more accurate predictions.

### Model Optimization
- **Hyperparameter Tuning**: Includes optimizing hidden layer dimensions, learning rates, and the choice of optimizers.
- **Collaborative Training Optimization**: Fine-tuning parameters to achieve the best performance.

## Results

The experiments demonstrated that the proposed deep learning model significantly outperforms traditional methods in predicting lncRNA-protein interactions. Key results include:

- **AUROC**: The model achieved an AUROC of 0.9424, higher than competing methods.
- **AUPR**: The model's AUPR was 0.8601, showing better precision and recall than other models.

The study also explored the potential of using Graph Attention Networks (GAT) for this task, with promising results that suggest further improvements are possible with more computational power.

## Conclusion

This thesis presents a deep learning approach that effectively predicts lncRNA-protein interactions, offering a powerful tool for molecular biology research. The model's superior performance compared to existing methods highlights the potential of deep learning in bioinformatics. Future work may focus on combining GCN and GAT layers or exploring variational autoencoders to further enhance prediction accuracy.

## Acknowledgments

I would like to express my deepest gratitude to my thesis advisor, **Prof. Han Zhang**, for his invaluable guidance and support throughout this project. I also thank my family, friends, and colleagues for their encouragement and assistance. This research was completed at the College of Artificial Intelligence, Nankai University.

## References

A comprehensive list of references is available in the thesis document, covering the foundational literature and recent advances in lncRNA-protein interaction prediction.

---

For more information, the full thesis document can be accessed [here](link-to-thesis-document). For any inquiries or further collaboration, please contact:

- **Qin Su**: [email@address.edu]
