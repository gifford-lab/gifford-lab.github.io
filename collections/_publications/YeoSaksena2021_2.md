---
title: "Generative modeling of single-cell time series with PRESCIENT enables prediction of cell trajectories with interventions"
authors: Grace Hui Ting Yeo*, Sachit D. Saksena*, and David K. Gifford
journal: "Nature Communications"
journalspecific:  "12, 3222 (2021)"
doi: "10.1038/s41467-021-23518-w"
arxiv: ""
ext: ""
img: Yeo2021_2.webp
date: "2021-05-28"
year: "2021"
---

Existing computational methods that use single-cell RNA-sequencing (scRNA-seq) for cell fate prediction do not model how cells evolve stochastically and in physical time, nor can they predict how differentiation trajectories are altered by proposed interventions. We introduce PRESCIENT (Potential eneRgy undErlying Single Cell gradIENTs), a generative modeling framework that learns an underlying differentiation landscape from time-series scRNA-seq data. We validate PRESCIENT on an experimental lineage tracing dataset, where we show that PRESCIENT is able to predict the fate biases of progenitor cells in hematopoiesis when accounting for cell proliferation, improving upon the best-performing existing method. We demonstrate how PRESCIENT can simulate trajectories for perturbed cells, recovering the expected effects of known modulators of cell fate in hematopoiesis and pancreatic β cell differentiation. PRESCIENT is able to accommodate complex perturbations of multiple genes, at different time points and from different starting cell populations, and is available at https://github.com/gifford-lab/prescient.
