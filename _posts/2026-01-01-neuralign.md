---
layout: post
type: "publication"
title:  "Unified Brain Surface and Volume Registration"
authors: "S. Mazdak Abulnaga, Andrew Hoopes, Malte Hoffmann, Robin Magnet, Maks Ovsjanikov, Lilla Zollei, John Guttag, Bruce Fischl*, Adrian V. Dalca*"
venue: "International Conference on Learning Representations (2016)"
external-url: "https://arxiv.org/pdf/2512.19928"
---
```
Accurate registration of brain MRI scans is fundamental for cross-subject analysis in neuroscientific studies. This involves aligning both the cortical surface
of the brain and the interior volume. Traditional methods treat volumetric and
surface-based registration separately, which often leads to inconsistencies that
limit downstream analyses. We propose a deep learning framework, NeurAlign,
that registers 3D brain MRI images by jointly aligning both cortical and subcortical regions through a unified volume-and-surface-based representation. Our
approach leverages an intermediate spherical coordinate space to bridge anatomical
surface topology with volumetric anatomy, enabling consistent and anatomically
accurate alignment. By integrating spherical registration into the learning, our
method ensures geometric coherence between volume and surface domains. In a
series of experiments on both in-domain and out-of-domain datasets, our method
consistently outperforms both classical and machine learning-based registration
methods–improving the Dice score by up to 7 points while maintaining regular
deformation fields. Additionally, it is orders of magnitude faster than the standard
method for this task, and is simpler to use because it requires no additional inputs
beyond an MRI scan. With its superior accuracy, fast inference, and ease of use,
NeurAlign sets a new standard for joint cortical and subcortical registration.
```
