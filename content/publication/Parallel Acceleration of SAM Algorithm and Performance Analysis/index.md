---
title: 'Parallel Acceleration of SAM Algorithm and Performance Analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haicheng Qu
  - Junping Zhang
  - Zhouhan Lin
  - Hao Chen

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

date: '2013-01-25T00:00:00Z'
doi: '10.1109/JSTARS.2013.2239261'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*
publication_short: In *IEEE*

abstract: Advances in sensor and computer technology are revolutionizing the way that remote sensing data with hundreds or even thousands of channels for the same area on the surface of the earth is collected, managed and analyzed. In this paper, the classical Spectral Angle Mapper (SAM) algorithm, which is fit for parallel and distributed computing, is implemented by using Graphic Processing Units (GPU) and distributed cluster respectively to accelerate the computations. A quantitative performance comparison between Compute Unified Device Architecture (CUDA) and MATLAB platform is given by analyzing result of different parallel architectures' implementation of the same SAM algorithm. Especially for the property of GPU, this paper studied the balance between resource acquirement of each thread and the number of active blocks, and the impact of computational complexity on speedup. In addition, page-locked memory and stream are also introduced to make CPU and GPU work collaboratively. Moreover, we improved the SAM algorithm, in which several training samples are instead of a single one. Experimental results on hyperspectral data have shown that recognition result of the improved SAM algorithm is better than that only using single spectrum. On the other hand, the GPU parallel implementation achieves a higher speedup comparing with the multithread CPU counterpart. And the asynchronous transfer function of CUDA covers the data transmission latency effectively, thus improves the devices' resource occupancy significantly.
# Summary. An optional shortened abstract.
summary: ''

tags: [High-performance computing, SAM, GPU, distributed computing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: https://ieeexplore.ieee.org/abstract/document/6844831
- name: PDF
  url: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6420972'
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
