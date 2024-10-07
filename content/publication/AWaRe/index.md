---
title: 'Reconstruction of Binary Black Hole Harmonics in LIGO Using Deep Learning'

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

date: '2024-06-26T00:00:00Z'
doi: '10.3847/1538-4357/ad4602'

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

abstract: Gravitational-wave signals from coalescing compact binaries in the LIGO and Virgo interferometers are primarily detected by the template-based matched filtering method. While this method is optimal for stationary and Gaussian data scenarios, its sensitivity is often affected by nonstationary noise transients in the detectors. Moreover, most of the current searches do not account for the effects of precession of black hole spins and higher-order waveform harmonics, focusing solely on the leading-order quadrupolar modes. This limitation impacts our search for interesting astrophysical sources, such as intermediate-mass black hole binaries and hierarchical mergers. Here we show, for the first time, that deep learning can be used for accurate waveform reconstruction of precessing binary black hole signals with higher-order modes. This approach can also be adapted into a rapid trigger generation algorithm to enhance online searches. Our model, tested on simulated injections in real LIGO noise from the third observing run (2019–2020) achieved a high degree of overlap with injected signals. This accuracy was consistent across a wide range of black hole masses and spin configurations chosen for this study. When applied to real gravitational-wave events, our model's reconstructions achieved between 85% and 98% overlap with those obtained by Coherent WaveBurst (unmodeled) and LALInference (modeled) analyses. These results suggest that deep learning is a potent tool for analyzing signals from a diverse catalog of compact binaries.
# Summary. An optional shortened abstract.
summary: We have developed a deep learning model, AWaRe, that is capable of producing accurate reconstructions of gravitational wave signals from real LIGO data. We demonstrate that the model is robust against complex waveform systematics like precession and the presence of higher multipoles.

tags: [Gravitational Waves, Deep Learning, Waveform Reconstruction, Precession, Higher-order modes] 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/ad4602
url_code: https://github.com/chayanchatterjee/AWaRe
url_dataset: ''
url_poster: ''
url_project: AWaRe
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Robustness of AWaRe reconstructions against the presence of higher-order modes in gravitational wave signals'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

projects: []

#projects:
#  - AWaRe

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

