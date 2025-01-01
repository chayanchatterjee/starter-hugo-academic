---
title: AWaRe
summary: Attention-boosted Waveform Reconstruction neural network for binary black holes
tags:
  - Attention 
  - Transformers
  - Binary Black Holes
  - Gravitational Waves
date: '2024-10-06T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/ChayanChirps
url_code: https://github.com/chayanchatterjee/AWaRe
url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/ad4602
#url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---
AWaRe (Attention-boosted Waveform Reconstruction) is a deep learning model designed for the accurate reconstruction of gravitational wave (GW) signals from black hole mergers using data from LIGO. The work addresses challenges in GW astronomy, such as the need for rapid and precise signal reconstruction in the presence of noise and complex waveform features like precession and higher-order harmonics, which are typically overlooked in standard template-based methods.

The first paper demonstrates AWaRe’s ability to reconstruct precessing binary black hole signals with higher-order modes, which are crucial for studying astrophysical sources like intermediate-mass black holes and hierarchical mergers. Tested on simulated injections in real LIGO noise, the model shows high overlap with injected signals and achieves accuracy levels comparable to traditional methods like Coherent WaveBurst (cWB) and LALInference, but at significantly faster speeds.

The second paper expands on this by introducing uncertainty estimation in AWaRe, enhancing its robustness and reliability when dealing with diverse waveforms, including those beyond the training set, such as eccentric and high-mass mergers. The model effectively generalizes to unseen data, producing uncertainty intervals consistent with established algorithms like BayesWave and cWB. This advancement is crucial for real-time detection and multimessenger follow-up observations, offering a promising tool for future studies in gravitational wave astrophysics and testing fundamental aspects of general relativity.

The third paper highlights the effectiveness of AWaRe in reconstructing GW signals from data contaminated by noise artifacts, or glitches, without requiring explicit training on glitch-augmented datasets. The model demonstrated remarkable robustness across various glitch types observed in LIGO's third observing run, accurately isolating GW signals with minimal contamination. Notably, AWaRe successfully reconstructed the waveforms of astrophysically significant events like GW191109 and GW200129, despite severe data quality issues caused by overlapping glitches. Additionally, systematic analyses of residual data, obtained by subtracting the reconstructed waveforms, revealed a strong agreement with the original glitch characteristics, underscoring the model's ability to disentangle noise from true signals. These findings establish AWaRe as a reliable and versatile tool for enhancing the accuracy of GW data analysis, even under challenging real-world conditions.

Related papers:
1. [Chayan Chatterjee and Karan Jani 2024 ApJ 969 25](https://iopscience.iop.org/article/10.3847/1538-4357/ad4602)
2. [Chayan Chatterjee and Karan Jani 2024 ApJ 973 112](https://iopscience.iop.org/article/10.3847/1538-4357/ad6984)
3. [Chayan Chatterjee and Karan Jani 2024 ArXiv](https://arxiv.org/abs/2412.17185)
