---
layout: post
type: "publication"
title:  "Multiple Instance Learning for ECG Risk Stratification"
authors: "D. Shanmugam, D. Blalock, J. Guttag"
venue: "MLHC 2019" 
external-url: "https://arxiv.org/abs/1812.00475"
slides: "https://dmshanmugam.github.io/pdfs/ecg_mlhc_slides.pdf"
poster: "https://dmshanmugam.github.io/pdfs/ecg_mlhc_poster.pdf"
---

Patients who suffer an acute coronary syndrome are at elevated risk for adverse cardiovascular events such as myocardial infarction and cardiovascular death. Accurate assessment of this risk is crucial to their course of care. We focus on estimating a patient's risk of cardiovascular death after an acute coronary syndrome based on a patient's raw electrocardiogram (ECG) signal. Learning from this signal is challenging for two reasons: 1) positive examples signifying a downstream cardiovascular event are scarce, causing drastic class imbalance, and 2) each patient's ECG signal consists of thousands of heartbeats, accompanied by a single label for the downstream outcome. Machine learning has been previously applied to this task, but most approaches rely on hand-crafted features and domain knowledge. We propose a method that learns a representation from the raw ECG signal by using a multiple instance learning framework. We present a learned risk score for cardiovascular death that outperforms existing risk metrics in predicting cardiovascular death within 30, 60, 90, and 365 days on a dataset of 5000 patients.

