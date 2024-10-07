---
title: 'Navigating Unknowns: Deep Learning Robustness for Gravitational Wave Signal Reconstruction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Karan Jani

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'

date: '2024-09-25T00:00:00Z'
doi: '10.3847/1538-4357/ad6984'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *The Astrophysical Journal*
publication_short: In *ApJ*

abstract: We present a rapid and reliable deep-learning-based method for gravitational-wave (GW) signal reconstruction from elusive, generic binary black hole mergers in LIGO data. We demonstrate that our model, AWaRe, effectively recovers GWs with parameters it has not encountered during training. This includes features like higher black hole masses, additional harmonics, eccentricity, and varied waveform systematics, which introduce complex modulations in the waveform's amplitudes and phases. The accurate reconstructions of these unseen signal characteristics demonstrate AWaRe's ability to handle complex features in the waveforms. By directly incorporating waveform reconstruction uncertainty estimation into the AWaRe framework, we show that for real GW events, the uncertainties in AWaRe's reconstructions align closely with those achieved by benchmark algorithms like BayesWave and coherent WaveBurst. The robustness of our model to real GW events and its ability to extrapolate to unseen data open new avenues for investigations in various aspects of GW astrophysics and data analysis, including tests of general relativity and the enhancement of current GW search methodologies.
# Summary. An optional shortened abstract.
summary: We extend the work in [Chatterjee & Jani, 2024](https://iopscience.iop.org/article/10.3847/1538-4357/ad4602) and demonstrate that AWaRe can be used to estimate gravitational wave reconstruction uncertainties. We further show that the uncertainties capture waveform systematics the model has not been trained on, including intermediate mass black holes and eccentricity.

tags: [Gravitational Waves, Deep Learning, Waveform Reconstruction, Higher-Order Modes, Eccentricity, Intermediate-Mass Black Holes] 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/ad6984
url_code: https://github.com/chayanchatterjee/AWaRe
url_dataset: ''
url_poster: ''
url_project: AWaRe_uncertainty
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Reconstruction of eccentric binary black hole gravitational wave signals using AWaRe'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

projects:
  - ANN_model

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

