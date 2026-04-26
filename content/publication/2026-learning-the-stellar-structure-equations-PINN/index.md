---
title: 'Learning the Stellar Structure Equations via Self-supervised Physics-Informed Neural Networks'

# Authors
# Using 'admin' for you and plain text for others to keep the UI clean
authors:
  - "Manuel Ballester"
  - "Santiago Lopez-Tapia"
  - "Seth Gossage"
  - admin
  - "Philipp M Srivastava"
  - "Ugur Demir"
  - "Yongseok Jo"
  - "Almudena P Marquez"
  - "Christoph Wuersch"
  - "Souvik Chakraborty"
  - "Vicky Kalogera"
  - "Aggelos Katsaggelos"

date: '2026-04-06'
doi: ''

# Schedule page publish date
publishDate: '2026-04-06'

publication_types: ['article']

# Publication name
publication: '*arXiv* preprint arXiv:2604.06255'
publication_short: 'arXiv'

abstract: "Stellar astrophysics relies critically on accurate descriptions of the physical conditions inside stars. Traditional solvers such as [MESA](https://docs.mesastar.org), which employ adaptive finite-difference methods, can become computationally expensive and challenging to scale for large stellar population synthesis. In this work, we present a self-supervised physics-informed neural network (PINN) framework that provides a mesh-free and fully differentiable approach to solving the stellar structure equations under hydrostatic and thermal equilibrium. The model takes as input the stellar boundary conditions together with the chemical composition, and learns continuous radial profiles for mass, pressure, density, temperature, and luminosity by enforcing the governing structure equations through physics-based loss terms. To incorporate realistic microphysics, we introduce auxiliary neural networks that approximate the equation of state and opacity tables as smooth, differentiable functions. Once trained, the model produces continuous solutions across the entire radial domain without requiring discretization or interpolation."

summary: "A self-supervised Physics-Informed Neural Network (PINN) framework for solving stellar structure equations as a mesh-free alternative to traditional solvers like MESA."

tags: ["Physics-Informed Neural Networks", "Stellar Astrophysics", "Self-supervised Learning", "MESA", "SIREN", "Equation of State", "Surrogate Modeling"]

featured: true

links:
- name: arXiv
  url: 'https://arxiv.org/abs/2604.06255'

# Featured image (e.g., a plot of PINN vs MESA radial profiles)
# Featured image
image:
  filename: "./pinn-stellar-structure.png"
  caption: 'Continuous radial profiles learned by the PINN framework.'
  focal_point: 'Smart'
  preview_only: false
---

[Manuel Ballester](https://3dim.optics.arizona.edu/author/manuel-ballester/), [Santiago Lopez-Tapia](https://sites.northwestern.edu/ivpl/people/), [Seth Gossage](https://sgossage.github.io/), **Patrick Koller**, [Philipp M Srivastava](https://sites.northwestern.edu/ivpl/people/), [Ugur Demir](https://sites.northwestern.edu/ivpl/people/), [Yongseok Jo](https://yongseokjo.com/), [Almudena P Marquez](https://scholar.google.com/citations?user=k3CRBwsAAAAJ&hl=es), [Christoph Würsch](https://www.ost.ch/en/person/christoph-wuersch-8300), [Souvik Chakraborty](https://www.csccm.in/our-team), [Vicky Kalogera](https://physics.northwestern.edu/people/faculty/core-faculty/vicky-kalogera.html), and [Aggelos K. Katsaggelos](https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/katsaggelos-aggelos.html)

### Abstract
This research introduces a mesh-free approach to solving the fundamental equations of stellar structure using Physics-Informed Neural Networks (PINNs). By enforcing hydrostatic and thermal equilibrium constraints directly within the loss function, we eliminate the need for traditional grid-based discretization used in solvers like [MESA](https://docs.mesastar.org). 

Our framework incorporates auxiliary neural surrogates for microphysics (opacities and equation of state), allowing the model to learn continuous, differentiable radial profiles across a wide range of stellar masses.

### BibTeX Citation
```bibtex
@misc{ballester2026learningstellarstructure,
      title={Learning the Stellar Structure Equations via Self-supervised Physics-Informed Neural Networks}, 
      author={Manuel Ballester and Santiago Lopez-Tapia and Seth Gossage and Patrick Koller and Philipp M. Srivastava and Ugur Demir and Yongseok Jo and Almudena P. Marquez and Christoph Wuersch and Souvik Chakraborty and Vicky Kalogera and Aggelos Katsaggelos},
      year={2026},
      eprint={2604.06255},
      archivePrefix={arXiv},
      primaryClass={astro-ph.SR},
      url={https://arxiv.org/abs/2604.06255}, 
}