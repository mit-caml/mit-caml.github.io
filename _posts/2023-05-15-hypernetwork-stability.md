---
layout: post
type: "publication"
title:  "Non-Proportional Parametrizations for Stable Hypernetwork Learning"
authors: "Jose Javier Gonzalez Ortiz, John Guttag, Adrian Dalca"
venue: "Preprint"
external-url: "https://arxiv.org/abs/NNNNNNNNN"
code: "https://github.com/JJGO/hyperlight"
---

In many scenarios current hypernetwork training strategies are unstable, and convergence is often far slower than for non-hypernetwork models.
We show that this problem is linked to an issue that arises  when using common choices of hypernetwork architecture and initialization.
We demonstrate analytically and experimentally how this numerical issue can lead to an instability during training that slows, and sometimes even prevents, convergence. We also demonstrate that popular deep learning normalization strategies fail to address these issues.
We then propose a solution to the problem based on a revised hypernetwork formulation that uses non-proportional additive parametrizations.
We test the proposed reparametrization on several tasks, and demonstrate that it consistently leads to more stable training, achieving faster convergence.
