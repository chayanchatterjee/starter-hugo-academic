---
title: GW-Whisper
summary: Application of OpenAI's Whisper for gravitational wave data analysis
tags:
  - Whisper
  - OpenAI
  - Gravitational Waves
  - Transformers
  - Foundational models
  - Audio Transformer
date: '2024-12-31T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/ChayanChirps
url_code: https://github.com/vanderbilt-data-science/GW-Whisper?tab=readme-ov-file
url_pdf: https://arxiv.org/abs/2412.20789
#url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---
This paper introduces GW-Whisper, an innovative application of OpenAI's Whisper model, originally designed for speech recognition, to gravitational wave (GW) data analysis. As the volume of data from advanced detectors like LIGO and Virgo grows, traditional methods face scalability challenges. GW-Whisper leverages Whisper’s pre-trained architecture to address critical tasks in GW astronomy, including signal detection and glitch classification, by fine-tuning the model using the parameter-efficient [DoRA method](https://arxiv.org/abs/2110.04366). This fine-tuning updates only 0.5% of the model's parameters, significantly reducing computational costs.

GW-Whisper processes GW strain data converted into log-mel spectrograms, aligning the input format with Whisper’s original design. The model's architecture, described in detail in the [Whisper documentation](https://arxiv.org/abs/2212.04356), includes a transformer-based encoder with convolutional layers and [multi-head attention mechanisms](https://arxiv.org/abs/1706.03762). The authors fine-tuned the encoder to classify GW signals from noise and categorize glitches into nine common types, achieving robust performance even at low signal-to-noise ratios (SNRs).

The model demonstrates near-perfect accuracy in distinguishing signals from noise, as shown by area-under-the-curve (AUC) scores of 1.0 for SNRs > 7 during early training epochs. For glitch classification, GW-Whisper achieves high accuracy across various noise scenarios, effectively distinguishing true GW events from artifacts resembling high-mass binary black hole signals. The glitch data used for this study was sourced from the [Gravitational Wave Open Science Center (GWOSC)](https://gwosc.org/), and the spectrogram extraction employed the [HuggingFace WhisperFeatureExtractor](https://huggingface.co/docs/transformers/en/model_doc/whisper).

Performance tests on real GW events from LIGO’s third observing run revealed GW-Whisper’s strong classification confidence, though challenges remain for weak or low-chirp-mass signals. The authors suggest expanding the training set to include more low-SNR and high-mass events to further improve performance. The implementation of GW-Whisper underscores the potential of foundational AI models, as highlighted in Bommasani et al., 2021, to revolutionize astrophysical data analysis by bridging AI advances with specialized scientific applications.

The study emphasizes the adaptability and scalability of GW-Whisper, positioning it as a practical tool for real-time GW data analysis in an era of increasing detection rates. This work paves the way for integrating pre-trained models into GW workflows, fostering innovation and collaboration in astrophysics. 

Related papers:
1. [Chatterjee et al 2024, ArXiv](https://arxiv.org/abs/2412.20789)
