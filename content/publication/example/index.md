---
title: 'Extraction of binary black hole gravitational wave signals from detector data using deep learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Linqing Wen
  - Foivos Diakogiannis
  - Kevin Vinsen

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'

date: '2021-09-16T00:00:00Z'
doi: '10.1103/PhysRevD.104.064046'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Physical Review D*
publication_short: In *PRD*

abstract: Accurate extractions of the detected gravitational wave (GW) signal waveforms are essential to validate a detection and to probe the astrophysics behind the sources producing the GWs. This however could be difficult in realistic scenarios where the signals detected by existing GW detectors could be contaminated with nonstationary and non-Gaussian noise. While the performance of existing waveform extraction methods are optimal, they are not fast enough for online application, which is important for multimessenger astronomy. In this paper, we demonstrate that a deep learning architecture consisting of convolutional neural network and bidirectional long short-term memory components can be used to extract binary black hole (BBH) GW waveforms from realistic noise in a few milliseconds. We have tested our network systematically on injected GW signals, with component masses uniformly distributed in the range of 10 to 80 solar mass, on Gaussian noise and Laser Interferometer Gravitational Wave Observatory (LIGO) detector noise. We find that our model can extract GW waveforms with overlaps of more than 0.95 with pure numerical relativity templates for signals with signal-to-noise ratio greater than six and is also robust against interfering “glitches”. We then apply our model to all ten detected BBH events from LIGO-Virgo’s first (O1) and second (O2) observation runs, obtaining ≥ 0.97 overlaps for all ten extracted BBH waveforms with the corresponding pure templates. We discuss the implication of our result and its future applications to GW localization and mass estimation.

# Summary. An optional shortened abstract.
summary: We demonstrate that a denoising autencoder model, consisting of a CNN encoder and a LSTM decoder can be used to extract binary black hole gravitational wave signals from Gaussian and real LIGO noise with high fidelity.

tags: [Denoising Autoencoder, Deep Learning, Gravitational Waves] 

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://journals.aps.org/prd/abstract/10.1103/PhysRevD.104.064046
url_code: ''
url_dataset: ''
url_poster: ''
url_project: example
url_source: ''
url_slides: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Performance of our denoising autoencoder model on ten real binary black hole events detected by LIGO.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

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
