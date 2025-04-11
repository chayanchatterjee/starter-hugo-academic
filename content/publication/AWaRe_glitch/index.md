---
title: 'No Glitch in the Matrix: Robust Reconstruction of Gravitational Wave Signals Under Noise Artifacts'

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

date: '2024-12-22T00:00:00Z'
doi: '10.3847/1538-4357/adbb66'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *ApJ*
publication_short: In *ApJ*

abstract: Gravitational wave observations by ground based detectors such as LIGO and Virgo have transformed astrophysics, enabling the study of compact binary systems and their mergers. However, transient noise artifacts, or glitches, pose a significant challenge, often obscuring or mimicking signals and complicating their analysis. In this work, we extend the Attention-boosted Waveform Reconstruction network to address glitch mitigation, demonstrating its robustness in reconstructing waveforms in the presence of real glitches from the third observing run of LIGO. Without requiring explicit training on glitches, AWaRe accurately isolates gravitational wave signals from data contaminated by glitches spanning a wide range of amplitudes and morphologies. We evaluate this capability by investigating the events GW191109 and GW200129, which exhibit strong evidence of anti-aligned spins and spin precession respectively, but may be adversely affected by data quality issues. We find that, regardless of the potential presence of glitches in the data, AWaRe reconstructs both waveforms with high accuracy. Additionally, we perform a systematic study of the performance of AWaRe on a simulated catalog of injected waveforms in real LIGO glitches and obtain reliable reconstructions of the waveforms. By subtracting the AWaRe reconstructions from the data, we show that the resulting residuals closely align with the background noise that the waveforms were injected in. The robustness of AWaRe in mitigating glitches, despite being trained exclusively on GW signals and not explicitly on glitches, highlights its potential as a powerful tool for improving the reliability of searches and characterizing noise artifacts.
# Summary. An optional shortened abstract.
summary: We show that AWaRe can accurately reconstruct gravitational wave signals from data containing overlapping noise artifacts called 'glitches', without being explictly trained on glitch data. 
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/adbb66
url_code: https://github.com/chayanchatterjee/AWaRe
url_dataset: ''
url_poster: ''
url_project: AWaRe_glitch
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
  - AWaRe_glitch

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

