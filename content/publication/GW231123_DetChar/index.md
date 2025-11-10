---
title: 'Machine Learning Confirms GW231123 is a “Lite” Intermediate-Mass Black Hole Merger'

authors:
  - admin
  - Kaylah McGowan
  - Suyash Deshmukh
  - Karan Jani

date: '2025-11-04T00:00:00Z'
doi: 'https://arxiv.org/abs/2509.09161'

# Schedule page publish date (when to show on the site, not the journal publication date)
publishDate: '2025-11-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and short version.
publication: 'In *The Astrophysical Journal Letters*'
publication_short: 'In *ApJL*'

abstract: >
  The LIGO–Virgo–KAGRA Collaboration recently reported GW231123, a black-hole merger
  with a total mass of around 190–265 solar masses. This event adds to the growing
  evidence of “lite” intermediate-mass black-hole (IMBH) discoveries, where the
  post-merger black hole exceeds 100 solar masses. GW231123 posed several data-analysis
  challenges owing to waveform-model systematics and the presence of noise artifacts
  called glitches. We present the first comprehensive machine-learning analysis to
  further validate this event, strengthen its astrophysical inference, and characterize
  instrumental noise in its vicinity. Our approach combines specialized tools for
  complementary analyses: **GW-Whisper**, an adaptation of OpenAI’s audio transformer;
  **ArchGEM**, a Gaussian-mixture-model–based soft clustering and density approximation
  software; and **AWaRe**, a convolutional autoencoder. We identify the data segment
  containing the merger with >70% confidence in both detectors and verify its astrophysical
  origin. We then characterize the scattered-light glitch around the event, providing
  the first physically interpretable parameters for this glitch. We also reconstruct
  the real waveforms from the data with slightly better agreement to model-agnostic
  reconstructions than to quasi-circular models, hinting at possible astrophysics beyond
  current waveform families (such as non-circular orbits or environmental imprints).
  Finally, by demonstrating high-fidelity waveform reconstructions for simulated mergers
  with total masses between 100–1000 solar masses, we show that our method can confidently
  probe the IMBH regime. Our integrated framework offers a powerful complementary tool
  to traditional pipelines for rapid, robust analysis of massive, glitch-contaminated events.

summary: >
  This study presents the first comprehensive machine-learning follow-up of the
  gravitational-wave event GW231123, the most massive binary black-hole merger detected
  to date (190–265 M⊙). Using three complementary AI tools—GW-Whisper (a Whisper-based
  transformer for signal classification), ArchGEM (a Gaussian-mixture model for glitch
  characterization), and AWaRe (an attention-based autoencoder for waveform reconstruction)—
  the work confirms the astrophysical origin of the event, extracts physical parameters
  of scattered-light glitches, and reconstructs the waveform with high fidelity. The
  framework demonstrates robust performance across simulated mergers up to 1000 M⊙,
  providing a scalable, model-agnostic approach for rapid validation of intermediate-mass
  black-hole mergers in noisy LIGO–Virgo–KAGRA data.

tags: [Gravitational Waves, Machine Learning, GW231123, Intermediate-Mass Black Holes]

featured: true

url_pdf: 'https://arxiv.org/abs/2509.09161'
url_code: 'https://github.com/chayanchatterjee/GW231123-ML-DetChar'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: >
    **Top:** Reconstructions of (a) Livingston and (b) Hanford data for GW231123 using AWaRe.
    The red dashed curves show the AWaRe mean reconstructions, and the red bands indicate
    associated reconstruction uncertainties. Reconstructions from cWB, Bilby, and BayesWave
    are shown in green, blue, and purple, respectively. The whitened noisy strains are shown
    in grey.  
    **Bottom:** Residuals obtained by subtracting the AWaRe mean reconstructions from
    the whitened strains.
  focal_point: ''
  preview_only: false

projects: []

slides: example
---
