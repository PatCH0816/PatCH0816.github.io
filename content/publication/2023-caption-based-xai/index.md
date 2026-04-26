---
title: 'Caption-Driven Explainability: Probing CNNs for Bias via CLIP'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - "Amil V. Dravid"
  - "Prof. Dr. Guido Schuster"
  - "Prof. Dr. Aggelos Katsaggelos"

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-01'
doi: '10.1109/ICIPW68931.2025.11386015'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: '[2025 IEEE International Conference on Image Processing Workshops (ICIPW)](https://2025.ieeeicip.org/)'
publication_short: 'IEEE ICIPW'

abstract: Robustness has become one of the most critical problems in machine learning (ML). The science of interpreting ML models to understand their behavior and improve their robustness is referred to as explainable artificial intelligence (XAI). One of the state-of-the-art XAI methods for computer vision problems is to generate saliency maps. A saliency map highlights the pixel space of an image that excites the ML model the most. However, this property could be misleading if spurious and salient features are present in overlapping pixel spaces. In this paper, we propose a caption-based XAI method, which integrates a standalone model to be explained into the contrastive language-image pre-training (CLIP) model using a novel network surgery approach. The resulting caption-based XAI model identifies the dominant concept that contributes the most to the models prediction. This explanation minimizes the risk of the standalone model falling for a covariate shift and contributes significantly towards developing robust ML models.

# Summary. An optional shortened abstract.
summary: This paper introduces a novel 'network surgery' approach that integrates CNNs with CLIP to provide caption-based explanations. By moving beyond potentially misleading saliency maps, this method identifies the dominant semantic concepts driving a model's prediction, enabling better detection of spurious biases and improving overall model robustness.

tags: ["Multi-Modal Explainability", "CLIP (Contrastive Language-Image Pre-training)", "Network Surgery", "Model Bias Detection", "IEEE ICIP"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: IEEE Xplore
  url: 'https://ieeexplore.ieee.org/abstract/document/11386015'
- name: arXiv
  url: 'https://arxiv.org/abs/2510.22035'

# url_pdf: 'https://arxiv.org/abs/2510.22035'
url_code: 'https://github.com/patch0816/caption-driven-xai'
url_dataset: ''
url_poster: 'https://www.ost.ch/fileadmin/dateiliste/97_daten/abstracts/34393c6e-51c7-43dd-b3e4-260f778b82f9.pdf'
url_project: ''
url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtu.be/m9Mx1BCNGFU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  filename: 'caption-driven-xai-clip-probing.png'
  caption: 'Framework for Caption-Driven XAI: Integrating target CNNs with CLIP via network surgery to identify semantic bias.'
  focal_point: 'smart'
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
**Patrick Koller**, [Amil V. Dravid](https://avdravid.github.io/), [Prof. Dr. Guido Schuster](https://www.barnes-schuster.ch/), and [Prof. Dr. Aggelos Katsaggelos](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/katsaggelos-aggelos.html)

Accepted and presented at the [IEEE ICIP 2025 Satellite Workshop](https://cmsworkshops.com/ICIP2025/view_paper.php?PaperNum=3069#top): "Generative AI for World Simulations and Communications & Celebrating 40 Years of Excellence in Education: Honoring Prof. Aggelos Katsaggelos," Anchorage, Alaska, USA, Sept 14, 2025.

### BibTeX Citation
```bibtex
@INPROCEEDINGS{Koller_2025_CaptionXAI,
  author={Koller, Patrick and Dravid, Amil V. and Schuster, Guido M. and Katsaggelos, Aggelos K.},
  booktitle={2025 IEEE International Conference on Image Processing Workshops (ICIPW)}, 
  title={Caption-Driven Explainability: Probing CNNS for Bias Via Clip}, 
  year={2025},
  volume={},
  number={},
  pages={663-667},
  keywords={Explainable AI;Computational modeling;Machine vision;Zero shot learning;Surgery;Medical services;Debugging;Predictive models;Robustness;Convolutional neural networks;Multi-Modal Explainability;CLIP;Model Bias Detection;Zero-Shot Learning;Network Surgery},
  doi={10.1109/ICIPW68931.2025.11386015}
}
