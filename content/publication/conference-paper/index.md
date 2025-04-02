---
title: 'Deep learning-based classification of hyperspectral data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yushi Chen
  - Zhouhan Lin
  - Xing Zhao
  - Gang Wang
  - Yanfeng Gu

# Author notes (optional)
author_notes:
  - ' corresponding author'

date: '2014-06-16T00:00:00Z'
doi: '10.1109/JSTARS.2014.2329330'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*
publication_short: In *IEEE*

abstract: Classification is one of the most popular topics in hyperspectral remote sensing. In the last two decades, a huge number of methods were proposed to deal with the hyperspectral data classification problem. However, most of them do not hierarchically extract deep features. In this paper, the concept of deep learning is introduced into hyperspectral data classification for the first time. First, we verify the eligibility of stacked autoencoders by following classical spectral information-based classification. Second, a new way of classifying with spatial-dominated information is proposed. We then propose a novel deep learning framework to merge the two features, from which we can get the highest classification accuracy. The framework is a hybrid of principle component analysis (PCA), deep learning architecture, and logistic regression. Specifically, as a deep learning architecture, stacked autoencoders are aimed to get useful high-level features. Experimental results with widely-used hyperspectral data indicate that classifiers built in this deep learning-based framework provide competitive performance. In addition, the proposed joint spectral-spatial deep neural network opens a new window for future research, showcasing the deep learning-based methods' huge potential for accurate hyperspectral data classification.
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
  url: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6844831'
url_code: 'https://github.com/hantek/deeplearn_hsi'
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

# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
