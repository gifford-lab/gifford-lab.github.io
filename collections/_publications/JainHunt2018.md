---
title: "Information-based Acquisition for General Models in Bayesian Optimization"
authors: "Siddhartha Jain, Nathan Hunt, and David Gifford"
journal: "Bayesian Deep Learning Workshop | NeurIPS 2019"
journalspecific:  ""
doi: ""
arxiv: ""
ext: "http://bayesiandeeplearning.org/2018/papers/147.pdf"
img: JainHunt2018.png
date: "2018-12-07"
year: "2018"
---

We introduce the Hilbert-Schmidt Independence Criterion (HSIC) Acquisition Function (HAF), an acquisition function for Bayesian optimization that uses HSIC to measure the statistical dependency to a distribution of interest. This enables extensions of information theoretic acquisition functions (e.g. entropy search variants) for more general models than just Gaussian Processes (GPs). HAF is also differentiable, so points can be acquired via gradient search on the input space. On a protein-DNA binding task we compare a particular instance of HAF with Thompson Sampling and Expected Reward. Though preliminary results are not impressive, we identify a major issue with the model used in this task and suggest a future direction to improve upon this work.
