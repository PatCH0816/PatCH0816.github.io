---
title: 'Size-Informed Representations for Unsupervised Image Clustering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Philipp Rajah Moura Srivastava
  - Charilaos Apostolidis
  - Saumya Pailwan
  - admin
  - Leandros Stefanopoulos

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-14'
doi: '10.1109/ICIPW68931.2025.11386144'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-14'

# Publication type.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: '[2025 IEEE International Conference on Image Processing Workshops (ICIPW)](https://2025.ieeeicip.org/)'
publication_short: 'IEEE ICIPW'

abstract: "Unsupervised image clustering aims to group unlabeled images into semantically meaningful categories without human supervision. While deep learning-based clustering frameworks such as semantic clustering by adopting neighbors (SCAN) and deep embedding clustering (DEC) have recently achieved promising results, the impact of preprocessing strategies—such as aspect-preserving padding and direct resizing—on clustering performance remains underexplored. This paper investigates both implicit size information (through preprocessing) and explicit size information injection in deep clustering frameworks, using a high-stakes, real-world dataset with significant image heterogeneity. We systematically evaluate SCAN and DINOv2-DEC clustering frameworks across multiple strategies: direct resizing, aspect ratio-preserving padding and late-fusion size injection with spectral encoding."

# Summary. An optional shortened abstract.
summary: "This paper investigates how image size and preprocessing impact unsupervised clustering, introducing a late-fusion size injection strategy that significantly improves performance on heterogeneous real-world datasets."

tags: ["Unsupervised Image Clustering", "Self-Supervised Learning", "Size Encoding", "Image Preprocessing", "Deep Embedded Clustering", "SCAN", "DINOv2", "IEEE ICIP"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: IEEE Xplore
  url: 'https://ieeexplore.ieee.org/document/11386144'

# url_pdf: 'https://arxiv.org/abs/2510.22035'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtu.be/m9Mx1BCNGFU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  filename: 'size-informed-clustering-pipeline.png'
  caption: 'Proposed framework for size-informed deep image clustering using late-fusion size injection.'
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
[Philipp Rajah Moura Srivastava](https://sites.northwestern.edu/ivpl/people/), [Charilaos Apostolidis](https://sites.northwestern.edu/ivpl/people/), [Saumya Pailwan](https://sites.northwestern.edu/ivpl/people/), **Patrick Koller**, and [Leandros Stefanopoulos](https://sites.northwestern.edu/ivpl/people/)

Accepted and presented at the [IEEE ICIP 2025 Satellite Workshop](https://cmsworkshops.com/ICIP2025/view_paper.php?PaperNum=3089): "Generative AI for World Simulations and Communications & Celebrating 40 Years of Excellence in Education: Honoring Prof. Aggelos Katsaggelos," Anchorage, Alaska, USA, Sept 14, 2025.

### BibTeX Citation
```bibtex
@INPROCEEDINGS{Srivastava_2025_SizeInformedClustering,
  author={Srivastava, Philipp Rajah Moura and Apostolidis, Charilaos and Pailwan, Saumya and Koller, Patrick and Stefanopoulos, Leandros},
  booktitle={2025 IEEE International Conference on Image Processing Workshops (ICIPW)}, 
  title={Size-Informed Representations for Unsupervised Image Clustering}, 
  year={2025},
  volume={},
  number={},
  pages={743-748},
  keywords={Visualization;Image coding;Conferences;Semantics;Pipelines;Data models;Image preprocessing;Standards;Unsupervised Image Clustering;SelfSupervised Learning;Size Encoding;Image Preprocessing;Deep Embedded Clustering},
  doi={10.1109/ICIPW68931.2025.11386144}}
