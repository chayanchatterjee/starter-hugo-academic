---
title: GW-SkyLocator
summary: Neural network for sky localization of gravitational waves, including pre-merger localization of binary neutron star mergers
tags:
  - Gravitational Waves
  - Compact Binary Coalescences
  - Deep Learning
  - Normalizing Flows
date: '2024-10-06T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/ChayanChirps
url_code: https://github.com/chayanchatterjee/GW-SkyLocator
url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/ad08b7
#url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---
GW-SkyLocator is a deep learning model designed for the rapid sky localization of gravitational wave (GW) sources from compact binary coalescences, such as binary black holes (BBH), binary neutron star (BNS) and neutron star-black hole (NSBH) mergers. These events often produce electromagnetic (EM) counterparts, making prompt localization critical for multimessenger astronomy. Traditional localization methods, which rely on Bayesian approaches, can be slow, taking anywhere from seconds to days, which poses challenges for detecting short-lived EM signals like gamma-ray bursts.

GW-SkyLocator uses a neural network architecture based on normalizing flows and ResNet, trained on signal-to-noise (S/N) time series derived from matched-filtering techniques. By using the S/N time series instead of the full GW strain data, the model efficiently extracts features, allowing it to infer sky location posteriors within seconds. This approach not only enhances the speed of localization but also supports premerger localization for BNS events, providing early warnings up to a minute before the merger. The premerger capabilities open up opportunities for EM follow-up of precursor emissions, enabling astronomers to observe a broader spectrum of phenomena associated with compact binary mergers.

Overall, the work showcases a significant advancement in the application of deep learning for GW astronomy, achieving rapid localization that supports both prompt and premerger observations, crucial for multimessenger studies.
 
Related publications: 
1. [Chayan Chatterjee et al 2023 ApJ 959 42](https://iopscience.iop.org/article/10.3847/1538-4357/ad08b7)
2. [Chayan Chatterjee and Linqing Wen 2023 ApJ 959 76](https://iopscience.iop.org/article/10.3847/1538-4357/accffb)
   

