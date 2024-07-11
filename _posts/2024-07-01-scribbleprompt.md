---
layout: post
type: "publication"
title:  "ScribblePrompt: Fast and Flexible Interactive Segmentation for Any Biomedical Image"
authors: "Hallee E. Wong, Marianne Rakic, John Guttag, Adrian V. Dalca"
venue: "European Conference on Computer Vision (ECCV) 2024"
external-url: "https://arxiv.org/abs/2312.07381"
code: "https://github.com/halleewong/ScribblePrompt"
website: "https://scribbleprompt.csail.mit.edu/"
video: "https://www.youtube.com/watch?v=L8CiAoHzPUE"
demo: https://huggingface.co/spaces/halleewong/ScribblePrompt
---

Biomedical image segmentation is a crucial part of both scientific research and clinical care. With enough labelled data, deep learning models can be trained to accurately automate specific biomedical image segmentation tasks. However, manually segmenting images to create training data is highly labor intensive and requires domain expertise. We present \emph{ScribblePrompt}, a flexible neural network based interactive segmentation tool for biomedical imaging that enables human annotators to segment previously unseen structures using scribbles, clicks, and bounding boxes. Through rigorous quantitative experiments, we demonstrate that given comparable amounts of interaction, ScribblePrompt produces more accurate segmentations than previous methods on datasets unseen during training. In a user study with domain experts, ScribblePrompt reduced annotation time by 28% while improving Dice by 15% compared to the next best method. ScribblePrompt's success rests on a set of careful design decisions. These include a training strategy that incorporates both a highly diverse set of images and tasks, novel algorithms for simulated user interactions and labels, and a network that enables fast inference. 