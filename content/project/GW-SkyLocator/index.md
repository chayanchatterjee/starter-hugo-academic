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
url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/ad08b7, https://iopscience.iop.org/article/10.3847/1538-4357/accffb
#url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---
Deep learning can be used to drastically decrease the processing time of parameter estimation for coalescing binaries of compact objects including black holes and neutron stars detected in gravitational waves (GWs). As a first step, we present two neural network models trained to rapidly estimate the posterior distributions of the chirp mass and mass ratio of a detected binary black hole system from the GW strain data of LIGO Hanford and Livingston Observatories. Using these parameters the component masses can be predicted, which has implications for the prediction of the likelihood that a merger contains a neutron star. The results are compared to the 'gold standard' of parameter estimation of gravitational waves used by the LIGO-Virgo Collaboration (LVC), LALInference. Our models predict posterior distributions consistent with that from LALInference while using orders of magnitude less processing time once the models are trained. The median predictions are within the 90% credible intervals of LALInference for all predicted parameters when tested on real binary black hole events detected during the LVC's first and second observing runs. We argue that deep learning has strong potential for low-latency high-accuracy parameter estimation suitable for real-time GW search pipelines.
 
Paper status: Submitted

