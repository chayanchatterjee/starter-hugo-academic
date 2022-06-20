---
title: 'Rapid Mass Parameter Estimation of Binary Black Hole Coalescences Using Deep Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alistair McLeod
  - Daniel Jacobs
  - admin
  - Linqing Wen
  - Fiona Panther

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'

date: '2022-01-26T00:00:00Z'
doi: '10.48550/arXiv.2201.11126'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *ArXiv*
publication_short: In *ArXiv*

abstract: Deep learning can be used to drastically decrease the processing time of parameter estimation for coalescing binaries of compact objects including black holes and neutron stars detected in gravitational waves (GWs). As a first step, we present two neural network models trained to rapidly estimate the posterior distributions of the chirp mass and mass ratio of a detected binary black hole system from the GW strain data of LIGO Hanford and Livingston Observatories. Using these parameters the component masses can be predicted, which has implications for the prediction of the likelihood that a merger contains a neutron star. The results are compared to the 'gold standard' of parameter estimation of gravitational waves used by the LIGO-Virgo Collaboration (LVC), LALInference. Our models predict posterior distributions consistent with that from LALInference while using orders of magnitude less processing time once the models are trained. The median predictions are within the 90% credible intervals of LALInference for all predicted parameters when tested on real binary black hole events detected during the LVC's first and second observing runs. We argue that deep learning has strong potential for low-latency high-accuracy parameter estimation suitable for real-time GW search pipelines.

# Summary. An optional shortened abstract.
summary:

tags: [Mass Estimation, Deep Learning, Gravitational Waves] 

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/abs/2201.11126
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
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
projects: []

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

