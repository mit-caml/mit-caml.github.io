---
layout: post
type: "publication"
title:  "Amortized Learning of Dynamic Feature Scaling for Image Segmentation"
authors: "Jose Javier Gonzalez Ortiz, John Guttag, Adrian Dalca"
venue: "Preprint"
external-url: "https://arxiv.org/abs/2304.05448"
code: "https://github.com/JJGO/scale-space-hypernetworks"
---

Convolutional Neural Networks (CNNs) are the predominant model used for a
variety of medical image analysis tasks. At inference time, these models are
computationally intensive, especially with volumetric data. In principle, it is
possible to trade accuracy for computational efficiency by manipulating the
rescaling factor in the downsample and upsample layers of CNN architectures.
However, properly exploring the accuracy-efficiency trade-off is prohibitively
expensive with existing models. To address this, we introduce Scale-Space
HyperNetworks (SSHN), a method that learns a spectrum of CNNs with varying
internal rescaling factors. A single SSHN characterizes an entire Pareto
accuracy-efficiency curve of models that match, and occasionally surpass, the
outcomes of training many separate networks with fixed rescaling factors. We
demonstrate the proposed approach in several medical image analysis
applications, comparing SSHN against strategies with both fixed and dynamic
rescaling factors. We find that SSHN consistently provides a better
accuracy-efficiency trade-off at a fraction of the training cost. Trained SSHNs
enable the user to quickly choose a rescaling factor that appropriately
balances accuracy and computational efficiency for their particular needs at
inference.
