---
title: 'Using deep learning to localize gravitational wave sources'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Linqing Wen
  - Kevin Vinsen
  - Manoj Kovalam
  - Amitava Datta

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'

date: '2019-11-26T00:00:00Z'
doi: '10.1103/PhysRevD.100.103025'

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

abstract: Deep learning algorithms, in particular neural networks, have been steadily gaining popularity among the gravitational wave community for the last few years. The reliability and accuracy of deep learning approaches in gravitational wave detection, parameter estimation, and glitch classification have already been proved and verified by several groups in recent years. In this paper, we report on the construction of the deep artificial neural network (ANN) to localize simulated gravitational wave signals in the sky with high accuracy. We have modeled the sky as a sphere and have considered cases in which the sphere is divided into 18, 50, 128, 1024, 2048, and 4096 sectors. The sky direction of the gravitational wave source is estimated by classifying the signal into one of these sectors based on its right ascension and declination values for each of these cases. To do this, we have injected simulated binary black hole gravitational wave signals of component masses sampled uniformly between 30 and 80 solar masses into Gaussian noise and used the whitened strain values to obtain the input features for training our ANN. We input features such as the delays in arrival times, phase differences, and amplitude ratios at each of the three detectors Hanford, Livingston, and Virgo, from the raw time-domain strain values as well as from analytical versions of these signals, obtained through Hilbert transformation. We show that our model is able to classify gravitational wave samples, not used in the training process, into their correct sectors with very high accuracy (greater than 90%) for coarse angular resolution using 18, 50, and 128 sectors. We also test our localization on test samples with injection parameters of the published LIGO binary black hole merger events GW150914, GW170818, and GW170823 for 1024, 2048, and 4096 sectors and compare the result with that from BAYESTAR and parameter estimation. In addition, we report that the time taken by our model to localize one gravitational wave signal is around 0.018 s on 14 Intel Xeon CPU cores.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Gravitational Waves, Deep Learning, Artificial Network, Classification] 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://journals.aps.org/prd/abstract/10.1103/PhysRevD.100.103025
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ANN_model
#url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Localization of GW150914 using our deep learning classification model'
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

