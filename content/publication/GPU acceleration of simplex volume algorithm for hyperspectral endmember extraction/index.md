---
title: 'GPU acceleration of simplex volume algorithm for hyperspectral endmember extraction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haicheng Qu
  - Junping Zhang
  - Zhouhan Lin
  - Hao Chen
  - Bormin Huang 

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

date: '2012-11-08T00:00:00Z'
doi: 'https://doi.org/10.1117/12.977956'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *High-Performance Computing in Remote Sensing II*
#publication_short: In *IGARSS2012*

abstract: The simplex volume algorithm (SVA)1 is an endmember extraction algorithm based on the geometrical properties of a simplex in the feature space of hyperspectral image. By utilizing the relation between a simplex volume and its corresponding parallelohedron volume in the high-dimensional space, the algorithm extracts endmembers from the initial hyperspectral image directly without the need of dimension reduction. It thus avoids the drawback of the N-FINDER algorithm, which requires the dimension of the data to be reduced to one less than the number of the endmembers. In this paper, we take advantage of the large-scale parallelism of CUDA (Compute Unified Device Architecture) to accelerate the computation of SVA on the NVidia GeForce 560 GPU. The time for computing a simplex volume increases with the number of endmembers. Experimental results show that the proposed GPU-based SVA achieves a significant 112.56x speedup for extracting 16 endmembers, as compared to its CPU-based single-threaded counterpart.
# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: https://ieeexplore.ieee.org/abstract/document/6844831

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
