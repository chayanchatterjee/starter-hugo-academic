---
title: 'Interpretable Analytic Formulae for GWTC-4 Binary Black Hole Population Properties via Symbolic Regression'

authors:
  - admin

date: '2026-08-07T00:00:00Z'
doi: '10.3847/1538-4357/ae88f4'

publishDate: '2026-08-07T00:00:00Z'

publication_types: ['2']

publication: 'In *The Astrophysical Journal*'
publication_short: 'In *ApJ*'

abstract: >
  Recent LIGO-Virgo-KAGRA analyses have revealed complex structure in the
  binary black hole population, including distinct features in the primary mass
  spectrum and nontrivial spin-mass correlations. However, phenomenological
  models used to capture these features often lack analytic transparency,
  making it difficult to isolate robust physical laws from modeling artifacts.
  This paper applies symbolic regression to posterior predictive samples from
  the GWTC-4 catalog, producing ensembles of closed-form surrogate expressions
  for merger-rate evolution with redshift, spin-population trends, and
  conditional mass-ratio distributions associated with the 10 and 35 solar-mass
  primary-mass peaks. The resulting formulae enable exact analytic gradient
  diagnostics and compact surrogate summaries for flexible population
  posteriors.

summary: >
  Symbolic regression turns GWTC-4 binary black-hole population posteriors into
  compact analytic formulae, making rate evolution, spin trends and mass-ratio
  structure easier to inspect and reuse.

tags:
  - Gravitational Waves
  - Binary Black Holes
  - Symbolic Regression
  - GWTC-4
  - Population Inference

featured: true

url_pdf: 'https://iopscience.iop.org/article/10.3847/1538-4357/ae88f4'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'Symbolic_Regression_BBH'
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Closed-form surrogate expressions for GWTC-4 binary black hole population properties.'
  focal_point: ''
  preview_only: false

projects:
  - Symbolic_Regression_BBH

slides: ''
---

The paper demonstrates how symbolic regression can compress flexible numerical population models into interpretable mathematical expressions. Those expressions can be differentiated exactly, compared across population features, and reused in forecasting, formation-channel studies and stochastic-background calculations.

| ![Fig. 1 from the ApJ paper showing BBH merger rate as a function of redshift](featured.png) |
|:--:|
| *Fig. 1: BBH comoving merger rate R(z) as a function of redshift. Shaded bands show the GWTC-4 90% credible intervals, while dashed lines show the corresponding PySR symbolic-regression median fits.* |
