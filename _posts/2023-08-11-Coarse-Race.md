---
layout: post
type: "publication"
title:  "Coarse race data conceals disparities in clinical risk score performance"
authors: "R. Movva*, D. Shanmugam*,  K. Hou, P. Pathak, J. Guttag, N. Garg, E. Pierson"
venue: "MLHC 2023"
external-url: "https://arxiv.org/abs/2304.09270"
code: "https://github.com/rmovva/granular-race-disparities_MLHC23"
---

Healthcare data in the United States often records only a patient's coarse race group: for example, both Indian and Chinese patients are typically coded as ``Asian.'' It is unknown, however, whether this coarse coding conceals meaningful disparities in the performance of clinical risk scores across granular race groups. Here we show that it does. Using data from 418K emergency department visits, we assess clinical risk score performance disparities across granular race groups for three outcomes, five risk scores, and four performance metrics. Across outcomes and metrics, we show that there are significant granular disparities in performance within coarse race categories. In fact, variation in performance metrics within coarse groups often exceeds the variation between coarse groups. We explore why these disparities arise, finding that outcome rates, feature distributions, and the relationships between features and outcomes all vary significantly across granular race categories. Our results suggest that healthcare providers, hospital systems, and machine learning researchers should strive to collect, release, and use granular race data in place of coarse race data, and that existing analyses may significantly underestimate racial disparities in performance.