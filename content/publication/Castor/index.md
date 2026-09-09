---
title: 'A Fast and Scalable Transformer Pipeline for Binary Black Hole Detection'

authors:
  - admin
  - Abigail Petulante
  - Haowei Fu
  - Yang Hu
  - Roy Lau
  - Karan Jani

date: '2026-08-31T20:34:23Z'
doi: 'https://arxiv.org/abs/2609.00339'

publishDate: '2026-08-31T20:34:23Z'

publication_types: ['3']

publication: 'In *arXiv*'
publication_short: 'In *arXiv*'

abstract: >
  With the projected increase in the detection rate of compact-binary
  coalescences in the coming decade, there is critical need to develop fast,
  robust, and scalable alternatives to matched filtering for
  gravitational-wave searches. Transformer models have revolutionized natural
  language and audio processing but their application to gravitational-wave
  astronomy is still largely unexplored. In this work, we introduce Castor, a
  transformer-based coincident search pipeline for detecting binary black hole
  gravitational-wave signals from Advanced LIGO detectors. One of the major
  features of our model is that it allows the false-alarm rate to be estimated
  via time slides cheaply without requiring repeated evaluations of the neural
  network. We evaluate Castor on datasets from the Machine-Learning
  Gravitational-Wave Search Challenge and on approximately five months of real
  O3b observing strain. Castor ranks among the most sensitive machine-learning
  pipelines, recovers the majority of confident GWTC-3 events within its
  training range, substantially outperforms GW-Whisper in sensitivity, and
  reduces the computational cost of background estimation by a factor of 20.

summary: >
  Castor is a compact time-domain transformer pipeline for binary black hole
  detection that enables efficient time-slide background estimation and strong
  sensitivity on benchmark and real LIGO data.

tags:
  - Gravitational Waves
  - Binary Black Holes
  - Transformers
  - Machine Learning
  - Castor
  - LIGO

featured: true

url_pdf: 'https://arxiv.org/pdf/2609.00339'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'Castor'
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Architecture of Castor, a coincident Siamese transformer pipeline for binary black hole detection.'
  focal_point: ''
  preview_only: false

projects:
  - Castor
  - GW-Whisper

slides: ''
---

Castor, the Coincident Analysis Siamese TransfORmer, is designed for scalable binary black hole searches in Advanced LIGO data. Each detector stream is processed independently using shared transformer weights, and the resulting single-detector outputs are combined into a coincident statistic. This allows time-slide backgrounds to be generated from cached network outputs instead of rerunning the neural network for every slide.

| ![Fig. 1 from the Castor paper showing the transformer search pipeline architecture](featured.png) |
|:--:|
| *Fig. 1: Castor tokenizes whitened H1 and L1 strain streams, processes them through shared transformer encoders, and combines single-detector log-odds and frame-localization profiles into a post-hoc coincident ranking statistic.* |
