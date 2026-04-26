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

date: '2026-04-15'
doi: ''

# Schedule page publish date
publishDate: '2026-04-15'

publication_types: ['article']

# Publication name
publication: '*arXiv* preprint arXiv:2604.13604'
publication_short: 'arXiv'

abstract: "Binary stellar evolution simulations are computationally expensive, yet they are fundamental to stellar population synthesis. While single-star track interpolation is straightforward, the interactions in binary systems—such as mass transfer and tidal forces—introduce discontinuities that make traditional methods inapplicable. In this work, we introduce a novel approach for track alignment and iterative track averaging based on Dynamic Time Warping (DTW). Our method computes a single shared warping path across all physical parameters simultaneously, placing them on a consistent temporal grid that preserves causal relationships. We demonstrate that this joint-alignment strategy maintains key physical laws, such as the Stefan-Boltzmann law, in the interpolated tracks, consistently outperforming standard interpolation methods across multiple binary configurations."

summary: "A novel track alignment and interpolation framework for binary stellar evolution using Dynamic Time Warping (DTW) to preserve physical consistency."

tags: ["Dynamic Time Warping", "Binary Stellar Evolution", "Time Series Interpolation", "Stellar Population Synthesis", "POSYDON", "Joint Alignment Strategy", "Computational Astrophysics"]

featured: true

links:
- name: arXiv
  url: 'https://arxiv.org/abs/2604.13604'

# Featured image (e.g., a plot showing aligned vs. misaligned binary tracks)
image:
  filename: "dtw-binary-alignment.png"
  caption: 'Shared warping path alignment for binary stellar tracks using DTW.'
  focal_point: ''
  preview_only: false
---

[Ugur Demir](https://sites.northwestern.edu/ivpl/people/), [Philipp M Srivastava](https://sites.northwestern.edu/ivpl/people/), [Aggelos K. Katsaggelos](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/katsaggelos-aggelos.html), [Vicky Kalogera](https://physics.northwestern.edu/people/faculty/core-faculty/vicky-kalogera.html), [Santiago L Tapia](https://sites.northwestern.edu/ivpl/people/), [Manuel Ballester](https://3dim.optics.arizona.edu/author/manuel-ballester/), [Shamal Lalvani](https://scholar.google.com/citations?user=o5u5qXEAAAAJ&hl=en), **Patrick Koller**, [Jeff J Andrews](https://phys.ufl.edu/people/faculty/jeff-andrews/), [Seth Gossage](https://sgossage.github.io/), [Max M Briel](https://maxbriel.com/), and [Elizabeth Teng](https://scholar.google.com/citations?user=gbFJzbMAAAAJ&hl=en)

### Abstract
This research addresses the computational bottleneck of population synthesis by introducing a robust interpolation scheme for binary stars. Unlike single-star evolution, binary tracks are often irregularly sampled and plagued by misaligned evolutionary phases due to mutual interactions.

By employing Dynamic Time Warping (DTW), we generate a joint alignment that preserves the underlying microphysics across the entire track, enabling the rapid generation of high-fidelity binary models for large-scale simulations like [POSYDON](https://posydon.org/).

### BibTeX Citation
```bibtex
@misc{demir2026irregularlysampledtimeseries,
      title={Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping}, 
      author={Ugur Demir and Philipp M. Srivastava and Aggelos Katsaggelos and Vicky Kalogera and Santiago L. Tapia and Manuel Ballester and Shamal Lalvani and Patrick Koller and Jeff J. Andrews and Seth Gossage and Max M. Briel and Elizabeth Teng},
      year={2026},
      eprint={2604.13604},
      archivePrefix={arXiv},
      primaryClass={astro-ph.SR},
      url={https://arxiv.org/abs/2604.13604}, 
}