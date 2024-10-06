---
title: 'Rapid Localization of Gravitational Wave Sources from Compact Binary Coalescences Using Deep Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Manoj Kovalam
  - Linqing Wen
  - Damon Beveridge
  - Foivos Diakogiannis
  - Kevin Vinsen

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'

date: '2023-12-05T00:00:00Z'
doi: '10.3847/1538-4357/ad08b7'

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

abstract: The mergers of neutron star–neutron star and neutron star–black hole binaries (NSBHs) are the most promising gravitational wave (GW) events with electromagnetic (EM) counterparts. The rapid detection, localization, and simultaneous multimessenger follow-up of these sources are of primary importance in the upcoming science runs of the LIGO-Virgo-KAGRA Collaboration. While prompt EM counterparts during binary mergers can last less than 2 s, the timescales of existing localization methods that use Bayesian techniques, vary from seconds to days. In this paper, we propose the first deep learning–based approach for rapid and accurate sky localization of all types of binary coalescences, including neutron star–neutron star and NSBHs for the first time. Specifically, we train and test a normalizing flow model on matched-filtering output from GW searches to obtain sky direction posteriors in around 1 s using a single P100 GPU, which is several orders of magnitude faster than full Bayesian techniques.
# Summary. An optional shortened abstract.
summary: We have developed a deep learning model, called GW-SkyLocator, to obtain the posterior distribution of the sky location of gravitational wave sources. This method is applicable for all three categories of compact binary coalescences - binary black holes, binary neutron stars and neutron star-black hole binaries.

tags: [Gravitational Waves, Deep Learning, Bayesian Infernce, Parameter Estimation] 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://iopscience.iop.org/article/10.3847/1538-4357/ad08b7
url_code: https://github.com/chayanchatterjee/GW-SkyLocator
url_dataset: ''
url_poster: ''
url_project: GW-SkyLocator
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Localization of gravitational wave sources using GW-SkyLocator'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

projects: []

#projects:
#  - ANN_model

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

