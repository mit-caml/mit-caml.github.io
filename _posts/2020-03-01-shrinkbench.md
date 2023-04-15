---
layout: post
type: "publication"
title:  "What is the State of Neural Network Pruning? "
authors: "Jose Javier Gonzalez Ortiz*, Davis Blalock*, Jonathan Frankle, John Guttag"
venue: "MLSys 2020"
external-url: "https://arxiv.org/abs/2003.03033"
code: "https://github.com/JJGO/shrinkbench"
slides: "https://josejg.com/slides/shrinkbench_sosp2019-slides.pdf"
poster: "https://josejg.com/posters/state_pruning_mlsys2020-poster.pdf"
---

Neural network pruning---the task of reducing the size of a network by removing parameters---has been the subject of a great deal of work in recent years. We provide a meta-analysis of the literature, including an overview of approaches to pruning and consistent findings in the literature. After aggregating results across 81 papers and pruning hundreds of models in controlled conditions, our clearest finding is that the community suffers from a lack of standardized benchmarks and metrics. This deficiency is substantial enough that it is hard to compare pruning techniques to one another or determine how much progress the field has made over the past three decades. To address this situation, we identify issues with current practices, suggest concrete remedies, and introduce ShrinkBench, an open-source framework to facilitate standardized evaluations of pruning methods. We use ShrinkBench to compare various pruning techniques and show that its comprehensive evaluation can prevent common pitfalls when comparing pruning methods.
