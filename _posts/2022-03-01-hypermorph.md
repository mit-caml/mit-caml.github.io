---
layout: post
type: "publication"
title:  "Learning the Effect of Registration Hyperparameters with HyperMorph"
authors: "Andrew Hoopes, Malte Hoffmann, Douglas N. Greve, Bruce Fischl, John Guttag, Adrian V. Dalca"
venue: "Machine Learning for Biomedical Imaging, 2022"
external-url: "https://www.melba-journal.org/pdf/2022:003.pdf"
code: "https://ahoopes.github.io/hypermorph"
video: "https://ahoopes.github.io/hypermorph"
---
  
We introduce HyperMorph, a framework that facilitates efficient hyperparameter tuning in
learning-based deformable image registration. Classical registration algorithms perform an
iterative pair-wise optimization to compute a deformation field that aligns two images.
Recent learning-based approaches leverage large image datasets to learn a function that
rapidly estimates a deformation for a given image pair. In both strategies, the accuracy of
the resulting spatial correspondences is strongly influenced by the choice of certain hyperparameter
values. However, an effective hyperparameter search consumes substantial time and human effort as it
often involves training multiple models for different fixed hyperparameter values and may lead to suboptimal
registration. We propose an amortized hyperparameter learning strategy to alleviate this burden by learning
the impact of hyperparameters on deformation fields. We design a meta network, or hypernetwork, that
predicts the parameters of a registration network for input hyperparameters, thereby comprising a single
model that generates the optimal deformation field corresponding to given hyperparameter values. This
strategy enables fast, high-resolution hyperparameter search at test-time, reducing the inefficiency
of traditional approaches while increasing flexibility. We also demonstrate additional benefits of HyperMorph,
including enhanced robustness to model initialization and the ability to rapidly identify optimal hyperparameter
values specific to a dataset, modality, task, or even anatomical region, all without the need to retrain models.
