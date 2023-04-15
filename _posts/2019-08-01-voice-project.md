---
layout: post
type: "publication"
title:  "Learning from Few Subjects with Large Amounts of Voice Monitoring Data"
authors: "Jose Javier Gonzalez Ortiz, Daryush Mehta, Jarrad Van Stan, Robert Hillman, John Guttag, Marzyeh Ghassemi "
venue: "Machine Learning for Healthcare 2019"
external-url: "https://josejg.com/papers/dvhm_mlhc2019.pdf"
---

Recently, researchers have started training high complexity machine learning models
to clinical tasks, often improving upon previous benchmarks. However, more often than
not, these methods require large amounts of supervision to provide good generalization
guarantees. When applied to data coming from small cohorts and long monitoring periods
these models are prone to overfit to subject-identifying features. Since obtaining large
amounts of labels is usually not practical in many scenarios, expert-driven knowledge of
the task is a common technique to prevent overfitting. We present a two-step learning
approach that is able to generalize under these circumstances when applied to a voice
monitoring dataset. Our approach decouples the feature learning stage and performs it in
an unsupervised manner, removing the need for laborious feature engineering. We show
the effectiveness of our proposed model on two voice monitoring related tasks. We evaluate
the extracted features for classifying between patients with vocal fold nodules and controls.
We also demonstrate that the features capture pathology relevant information by showing
that models trained on them are more accurate predicting vocal use for patients than for
controls. Our proposed method is able to generalize to unseen subjects and across learning
tasks while matching state-of-the-art results.
