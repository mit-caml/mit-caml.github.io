---
layout: post
type: "publication"
title:  "Shape-aware Segmentation of the Placenta in BOLD Fetal MRI Time Series"
authors: "S. Mazdak Abulnaga, Neel Dey, Sean I. Young, Katherine Hobgood, Eileen Pan, Clinton J. Wang, P. Ellen Grant, Esra Abaci Turk, Polina Golland"
venue: "Machine Learning for Biomedical Imaging (MELBA)"
external-url: "https://arxiv.org/abs/2312.05148"
code: "https://github.com/mabulnaga/automatic-placenta-segmentation/"
---

Blood oxygen level dependent (BOLD) MRI time series with maternal hyperoxia can assess placental oxygenation and function. Measuring precise BOLD changes in the placenta requires accurate temporal placental segmentation and is confounded by fetal and maternal motion, contractions, and hyperoxia-induced intensity changes. Current BOLD placenta segmentation methods warp a manually annotated subject-specific template to the entire time series. However, as the placenta is a thin, elongated, and highly non-rigid organ subject to large deformations and obfuscated edges, existing work cannot accurately segment the placental shape, especially near boundaries. In this work, we propose a machine learning segmentation framework for placental BOLD MRI and apply it to segmenting each volume in a time series. We use a placental-boundary weighted loss formulation and perform a comprehensive evaluation across several popular segmentation objectives. Our model is trained and tested on a cohort of 91 subjects containing healthy fetuses, fetuses with fetal growth restriction, and mothers with high BMI. Biomedically, our model performs reliably in segmenting volumes in both normoxic and hyperoxic points in the BOLD time series. We further find that boundary-weighting increases placental segmentation performance by 8.3% and 6.0% Dice coefficient for the cross-entropy and signed distance transform objectives, respectively.
