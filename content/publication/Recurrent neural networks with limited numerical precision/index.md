---
title: 'Recurrent neural networks with limited numerical precision'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhouhan Lin
  - Joachim Ott
  - Ying Zhang
  - Shih-Chii Liu
  - Yoshua Bengio
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''

date: '2016-08-24T00:00:00Z'
doi: ' 	arXiv:1608.06902'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Efficient Methods for Deep Neural Networks on 29th Annual Conference on Neural Information Processing Systems*
publication_short: In *ICML 2015 workshop*

abstract: Recurrent Neural Networks (RNNs) produce state-of-art performance on many machine learning tasks but their demand on resources in terms of memory and computational power are often high. Therefore, there is a great interest in optimizing the computations performed with these models especially when considering development of specialized low-power hardware for deep networks. One way of reducing the computational needs is to limit the numerical precision of the network weights and biases. This has led to different proposed rounding methods which have been applied so far to only Convolutional Neural Networks and Fully-Connected Networks. This paper addresses the question of how to best reduce weight precision during training in the case of RNNs. We present results from the use of different stochastic and deterministic reduced precision training methods applied to three major RNN types which are then tested on several datasets. The results show that the weight binarization methods do not work with the RNNs. However, the stochastic and deterministic ternarization, and pow2-ternarization methods gave rise to low-precision RNNs that produce similar and even higher accuracy on certain datasets therefore providing a path towards training more efficient implementations of RNNs in specialized hardware.
# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: https://ieeexplore.ieee.org/abstract/document/6844831
- name: PDF
  url: 'https://arxiv.org/pdf/1608.06902'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- # {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
