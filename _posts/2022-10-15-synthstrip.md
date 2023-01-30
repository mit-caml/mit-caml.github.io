---
layout: post
type: "publication"
title:  "SynthStrip: Skull-Stripping for Any Brain Image"
authors: "A. Hoopes, J. Mora, A. Dalca, B. Fischl, M. Hoffmann"
venue: "NeuroImage 2022" 
external-url: "https://arxiv.org/pdf/2203.09974.pdf"
code: "https://surfer.nmr.mgh.harvard.edu/docs/synthstrip"
video: "https://surfer.nmr.mgh.harvard.edu/docs/synthstrip"
---

The removal of non-brain signal from magnetic resonance imaging (MRI) data, known as skull-stripping, is an integral component of many neuroimage analysis streams. Despite their abundance, popular classical skull-stripping methods are usually tailored to images with specific acquisition properties, namely near-isotropic resolution and T1-weighted (T1w) MRI contrast, which are prevalent in research settings. As a result, existing tools tend to adapt poorly to other image types, such as stacks of thick slices acquired with fast spin-echo (FSE) MRI that are common in the clinic. While learning-based approaches for brain extraction have gained traction in recent years, these methods face a similar burden, as they are only effective for image types seen during the training procedure. To achieve robust skull-stripping across a landscape of imaging protocols, we introduce SynthStrip, a rapid, learning-based brain-extraction tool. By leveraging anatomical segmentations to generate an entirely synthetic training dataset with anatomies, intensity distributions, and artifacts that far exceed the realistic range of medical images, SynthStrip learns to successfully generalize to a variety of real acquired brain images, removing the need for training data with target contrasts. We demonstrate the efficacy of SynthStrip for a diverse set of image acquisitions and resolutions across subject populations, ranging from newborn to adult. We show substantial improvements in accuracy over popular skull-stripping baselines – all with a single trained model.
