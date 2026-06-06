---
title: 'Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping'

# Authors
# Using 'admin' for you and plain text for others to keep the UI clean
authors:
  - "Ugur Demir"
  - "Philipp M Srivastava"
  - "Aggelos Katsaggelos"
  - "Vicky Kalogera"
  - "Santiago L Tapia"
  - "Manuel Ballester"
  - "Shamal Lalvani"
  - admin
  - "Jeff J Andrews"
  - "Seth Gossage"
  - "Max M Briel"
  - "Elizabeth Teng"

date: '2026-06-05'
doi: '10.3847/1538-4357/ae63c6'

# Schedule page publish date
publishDate: '2026-06-05'

publication_types: ['2']

# Publication name
publication: '*The Astrophysical Journal*, 1004(1), 78'
publication_short: '*ApJ*'

abstract: "Binary stellar evolution simulations are computationally expensive, yet they are fundamental to stellar population synthesis. While single-star track interpolation is straightforward, interactions in binary systems, such as mass transfer and tidal forces, introduce discontinuities that make traditional methods inapplicable. In this work, we introduce a novel approach for track alignment and iterative track averaging based on Dynamic Time Warping (DTW). Our method computes a single shared warping path across all physical parameters simultaneously, placing them on a consistent temporal grid that preserves causal relationships. We demonstrate that this joint-alignment strategy maintains key physical laws, such as the Stefan-Boltzmann law, in the interpolated tracks, consistently outperforming standard interpolation methods across multiple binary configurations."

summary: "A novel track alignment and interpolation framework for binary stellar evolution using Dynamic Time Warping (DTW) to preserve physical consistency."

tags: ["Dynamic Time Warping", "Binary Stellar Evolution", "Time Series Interpolation", "Stellar Population Synthesis", "POSYDON", "Joint Alignment Strategy", "Computational Astrophysics"]

featured: true

links:
- name: Journal
  url: 'https://doi.org/10.3847/1538-4357/ae63c6'
- name: arXiv
  url: 'https://arxiv.org/abs/2604.13604'

# Featured image (e.g., a plot showing aligned vs. misaligned binary tracks)
image:
  filename: "dtw-binary-alignment.png"
  caption: 'Shared warping path alignment for binary stellar tracks using DTW.'
  focal_point: 'smart'
  preview_only: false
---

[Ugur Demir](https://sites.northwestern.edu/ivpl/people/), [Philipp M Srivastava](https://sites.northwestern.edu/ivpl/people/), [Aggelos K. Katsaggelos](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/katsaggelos-aggelos.html), [Vicky Kalogera](https://physics.northwestern.edu/people/faculty/core-faculty/vicky-kalogera.html), [Santiago L Tapia](https://sites.northwestern.edu/ivpl/people/), [Manuel Ballester](https://3dim.optics.arizona.edu/author/manuel-ballester/), [Shamal Lalvani](https://scholar.google.com/citations?user=o5u5qXEAAAAJ&hl=en), **Patrick Koller**, [Jeff J Andrews](https://phys.ufl.edu/people/faculty/jeff-andrews/), [Seth Gossage](https://sgossage.github.io/), [Max M Briel](https://maxbriel.com/), and [Elizabeth Teng](https://scholar.google.com/citations?user=gbFJzbMAAAAJ&hl=en)

### BibTeX Citation
```bibtex
@article{Demir_2026,
  doi       = {10.3847/1538-4357/ae63c6},
  url       = {https://doi.org/10.3847/1538-4357/ae63c6},
  year      = {2026},
  month     = {jun},
  publisher = {The American Astronomical Society},
  volume    = {1004},
  number    = {1},
  pages     = {78},
  author    = {Demir, Ugur and Srivastava, Philipp M. and Katsaggelos, Aggelos and Kalogera, Vicky and Tapia, Santiago L. and Ballester, Manuel and Lalvani, Shamal and Koller, Patrick and Andrews, Jeff J. and Gossage, Seth and Briel, Max M. and Teng, Elizabeth},
  title     = {Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping},
  journal   = {The Astrophysical Journal}
}