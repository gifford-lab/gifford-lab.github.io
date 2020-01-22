---
title: "What made you do this? Understanding black-box decisions with sufficient input subsets"
authors: "Brandon Carter, Jonas Mueller, Siddhartha Jain, and David Gifford"
journal: "arXiv"
journalspecific:  "preprint arXiv:1810.03805"
doi: ""
arxiv: "1810.03805"
ext: ""
img: Carter2019.png
date: "2019-02-08"
year: "2019"
---

Local explanation frameworks aim to rationalize particular decisions made by a black-box prediction model. Existing techniques are often restricted to a specific type of predictor or based on input saliency, which may be undesirably sensitive to factors unrelated to the model's decision making process. We instead propose sufficient input subsets that identify minimal subsets of features whose observed values alone suffice for the same decision to be reached, even if all other input feature values are missing. General principles that globally govern a model's decision-making can also be revealed by searching for clusters of such input patterns across many data points. Our approach is conceptually straightforward, entirely model-agnostic, simply implemented using instance-wise backward selection, and able to produce more concise rationales than existing techniques. We demonstrate the utility of our interpretation method on various neural network models trained on text, image, and genomic data.
