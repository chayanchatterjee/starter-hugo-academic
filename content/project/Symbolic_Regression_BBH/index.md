---
title: Interpretable Binary Black Hole Population Inference
summary: Symbolic regression methods for turning GWTC-4 population posteriors into compact, differentiable analytic formulae.
tags:
  - Symbolic Regression
  - Binary Black Holes
  - Population Inference
  - GWTC-4
  - Gravitational Waves
date: '2026-08-07T00:00:00Z'

external_link: ''

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/ChayanChirps
url_code: ''
url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/ae88f4
url_video: ''

slides:
---

This project develops interpretable analytic summaries of binary black hole population properties inferred from the GWTC-4 catalog. Instead of treating flexible population models as opaque numerical objects, symbolic regression is used to learn closed-form surrogate expressions for merger-rate evolution, spin-population trends and mass-ratio structure near the primary-mass peaks.

The resulting formulae make it possible to inspect gradients exactly, compare features across model families and pass compact population summaries into downstream calculations such as rate forecasting, formation-channel comparisons and stochastic-background estimates.

| ![Fig. 1 from the ApJ paper showing BBH merger rate as a function of redshift](featured.png) |
|:--:|
| *Fig. 1: Symbolic-regression surrogates reproduce GWTC-4 binary black hole merger-rate trends while preserving posterior uncertainty across model families.* |

Related papers:
1. [Chayan Chatterjee 2026, ApJ](https://iopscience.iop.org/article/10.3847/1538-4357/ae88f4)
