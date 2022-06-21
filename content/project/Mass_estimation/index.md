---
title: Rapid Mass Parameter Estimation of Binary Black Hole Coalescences Using Deep Learning
summary: A deep learning-based workflow for denoising and estimating black hole masses from gravitational wave data.
tags:
  - Denoising Autoencoder 
  - Gravitational Waves
  - Binary Black Holes
  - Deep Learning
  - Convolutional Neural Network
date: '2022-01-26T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/ChayanChirps
url_code: https://github.com/chayanchatterjee/GW-Denoiser
url_pdf: https://arxiv.org/abs/2201.11126
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

