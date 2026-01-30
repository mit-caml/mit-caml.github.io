---
layout: post
type: "publication"
title:  "AtlasMorph: Learning conditional deformable templates for brain MRI"
authors: "Marianne Rakic, Andrew Hoopes, S Mazdak Abulnaga, Mert R Sabuncu, John V Guttag, Adrian V Dalca"
venue: "Medical Image Analysis"
external-url: "https://arxiv.org/pdf/2511.13609"
---
Deformable templates, or atlases, are images that represent
a prototypical anatomy for a population, and are often enhanced with probabilistic anatomical label maps. They are
commonly used in medical image analysis for population
studies and computational anatomy tasks such as registration and segmentation. Because developing a template is a
computationally expensive process, relatively few templates
are available. As a result, analysis is often conducted with
sub-optimal templates that are not truly representative of
the study population, especially when there are large variations within this population.
We propose a machine learning framework that uses convolutional registration neural networks to efficiently learn
a function that outputs templates conditioned on subjectspecific attributes, such as age and sex. We also leverage
segmentations, when available, to produce anatomical segmentation maps for the resulting templates. The learned
network can also be used to register subject images to the
templates. We demonstrate our method on a compilation of
3D brain MRI datasets, and show that it can learn highquality templates that are representative of populations. We
find that annotated conditional templates enable better registration than their unlabeled unconditional counterparts,
and outperform other templates construction methods.
