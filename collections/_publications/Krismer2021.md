---
title: "seqgra: Principled Selection of Neural Network Architectures for Genomics Prediction Tasks"
authors: "Konstantin Krismer, Jennifer Hammelman, David K. Gifford"
journal: "bioRxiv"
journalspecific:  ""
doi: "10.1101/2021.06.14.448415"
arxiv: ""
ext: ""
img: Krismer2021.png
date: "2021-06-15"
year: "2021"
---

Sequence models based on deep neural networks have achieved state-of-the-art performance on regulatory genomics prediction tasks, such as chromatin accessibility and transcription factor binding. But despite their high accuracy, their contributions to a mechanistic understanding of the biology of regulatory elements is often hindered by the complexity of the predictive model and thus poor interpretability of its decision boundaries. To address this, we introduce seqgra, a deep learning pipeline that incorporates the rule-based simulation of biological sequence data and the training and evaluation of models, whose decision boundaries mirror the rules from the simulation process. The method can be used to (1) generate data under the assumption of a hypothesized model of genome regulation, (2) identify neural network architectures capable of recovering the rules of said model, and (3) analyze a model’s predictive performance as a function of training set size, noise level, and the complexity of the rules behind the simulated data.
