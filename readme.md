<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome List of Bayesian Optimization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint]

<!-- subtitle -->

Bayesian optimization has emerged as a powerful tool in materials science and chemistry, enabling efficient exploration of vast chemical spaces and accelerating the discovery of novel materials with desired properties. By intelligently balancing exploration and exploitation, Bayesian optimization algorithms can guide experiments and simulations towards promising regions of the search space, reducing the number of trials required to find optimal solutions. This awesome list curates a collection of software, tutorials, research papers, and other resources related to Bayesian optimization in materials science and chemistry.

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="" />
</a>

<!-- description -->

An Awesome List of Bayesian Optimization resources, software, and tools.

</div>

<!-- TOC -->

## Contents

- [Tutorials](#tutorials)
- [Software](#software)
- [Papers](#papers)
- [Datasets](#datasets)
- [Conferences Workshops and Hackathons]()

<!-- CONTENT -->

## Tutorials


## Software

- [Adaptive Experimentation Platform (Ax)](https://ax.dev/) is a user-friendly, modular, and actively developed general-purpose Bayesian optimization platform with support for simple and advanced optimization tasks such as noisy, multi-objective, multi-task, multi-fidelity, batch, high-dimensional, linearly constrained, nonlinearly constrained, mixed continuous/discrete/categorical, and contextual Bayesian optimization.
- [BoTorch](https://botorch.org/) is the backbone that makes up the Ax platform and allows for greater customization and specialized algorithms such as risk-averse Bayesian optimization and constraint active search.
- [Dragonfly](https://github.com/dragonfly/dragonfly) is an open source python library for scalable Bayesian optimization with multi-objective and multi-fidelity support.
- [RayTune](https://docs.ray.io/en/latest/tune/index.html) offers experiment execution and hyperparameter tuning at any scale with many supported [search algorithms](https://docs.ray.io/en/latest/tune/api/suggestion.html) and [trial schedulers](https://docs.ray.io/en/latest/tune/api/schedulers.html) under a common interface.
- Aspuru-Guzik Group
  - [Atlas](https://github.com/rileyhickman/atlas) is a Python package that offers Bayesian optimization tailored towards real-world experimental science problems: mixed parameters, multi-objective, noisy, constrained, multi-fidelity, and meta-learning optimization along with search space expansion/contraction. [WIP]
  - [Chimera](https://github.com/aspuru-guzik-group/chimera) is a hierarchy-based multi-objective optimization scalarizing function.
  - [Gryffin](https://github.com/aspuru-guzik-group/gryffin) enables Bayesian optimization of continuous and categorical variables with support for physicochemical descriptors and batch optimization.
  - [Gemini](https://github.com/aspuru-guzik-group/gemini) is a scalable multi-fidelity Bayesian optimization technique and is supported by Gryffin.
  - [Golem](https://github.com/aspuru-guzik-group/golem) is an algorithm that helps identify optimal solutions that are robust to input uncertainty (i.e., robust optimization).
  - [Phoenics](https://github.com/aspuru-guzik-group/phoenics) is a linear-scaling Bayesian optimization algorithm with support for batch and periodic parameter optimization.
  - [Anubis](https://github.com/aspuru-guzik-group/atlas-unknown-constraints) is a Bayesian optimization algorithm that models unknown feasibility constraints and incorporates it into the acquisition function
- [BoFire](https://github.com/experimental-design/bofire) is a **B**ayesian **O**ptimization **F**ramework **I**ntended for **R**eal **E**xperiments (under development) with support for advanced optimization tasks such as mixed variables, multiple objectives, and generic constraints.
- [NIMS-OS](https://github.com/nimsos-dev/nimsos) is a Python package (+GUI) for
  workflow orchestration and multi-objective optimization software that supports [BLOX](https://github.com/tsudalab/BLOX), [PDC](https://github.com/tsudalab/PDC),
  random exploration, and a multi-objective variant of [PHYSBO](https://github.com/issp-center-dev/PHYSBO).
- [SLAMD](https://github.com/BAMresearch/WEBSLAMD) - A web app leveraging data-driven design for cementitious materials via a digital lab twin, complemented by a (materials-agnostic) AI optimization feature. Features UI to interactively explore  design spaces. The web app uses Python and Javascript.
- [Summit](https://github.com/sustainable-processes/summit) is a set of tools for optimizing chemical processes with a wide variety of design of experiments (DoE) and adaptive design methods along with benchmarks.
- [GPax](https://github.com/ziatdinovmax/gpax) is a Python package for physics-based Gaussian processes (GPs) built on top of NumPyro and JAX that take advantage of prior physical knowledge and different data modalities for active learning and Bayesian optimization. It supports "deep kernel learning", structured probabilistic mean functions, hypothesis learning workflows, multitask, multifidelity, heteroscedastic, and vector BO and emphasizes user friendliness.
- [Bayesian Back End (BayBE)](https://github.com/emdgroup/baybe) is a open-source toolbox by [Merck KGaA](https://www.merckgroup.com/) for Bayesian optimization, featuring custom encodings, chemical knowledge integration, hybrid spaces, transfer learning, simulation tools, and robust, serializable code for real-world experimental campaigns.

### Proprietary
- [ChemOS](https://chemos.io/)
- [The Citrine Platform](https://citrine.io/product/what-is-the-citrine-platform/)
- IBM Accelerated Discovery
  - [RXN for Chemistry](https://rxn.res.ibm.com/)
  - [Simulation Toolkit For Scientific Discovery (ST4SD)](https://st4sd.github.io/overview/)
  - [Generative Toolkit for Scientific Discovery](https://gt4sd.github.io/gt4sd-core/)
  - [Deep Search](https://ds4sd.github.io/) (semantic extraction from documents)

<!-- END CONTENT -->

## Datasets

## Papers

## Conferences, Workshops, and Hackathons

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/materials-data-facility/awesome-bayesian-optimization/graphs/contributors)!
