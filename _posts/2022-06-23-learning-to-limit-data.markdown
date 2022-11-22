---
layout: post
type: "publication"
title:  "Learning to Limit Data Collection via Scaling Laws: A Computational Interpretation for the Legal Principle of Data Minimization"
authors: "D. Shanmugam, F. Diaz, S. Shabanian, M. Finck, A. Biega"
venue: "FAccT 2021" 
external-url: "https://dl.acm.org/doi/abs/10.1145/3531146.3533148"
---

Modern machine learning systems are increasingly characterized by extensive personal data collection, despite the diminishing returns and increasing societal costs of such practices. Yet, data minimisation is one of the core data protection principles enshrined in the European Union’s General Data Protection Regulation (’GDPR’) and requires that only personal data that is adequate, relevant and limited to what is necessary is processed. However, the principle has seen limited adoption due to the lack of technical interpretation. <br>

In this work, we build on literature in machine learning and law to propose FIDO, a Framework for Inhibiting Data Overcollection. FIDO learns to limit data collection based on an interpretation of data minimization tied to system performance. Concretely, FIDO provides a data collection stopping criterion by iteratively updating an estimate of the performance curve, or the relationship between dataset size and performance, as data is acquired. FIDO estimates the performance curve via a piecewise power law technique that models distinct phases of an algorithm’s performance throughout data collection separately. Empirical experiments show that the framework produces accurate performance curves and data collection stopping criteria across datasets and feature acquisition algorithms. We further demonstrate that many other families of curves systematically overestimate the return on additional data. Results and analysis from our investigation offer deeper insights into the relevant considerations when designing a data minimization framework, including the impacts of active feature acquisition on individual users and the feasability of user-specific data minimization. We conclude with practical recommendations for the implementation of data minimization.