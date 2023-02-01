---
title: "AODisaggregation: toward global aerosol vertical profiles"
authors: 'S. Bouabid, D. Watson-Parris, S. Stefanovic, A. Nenes, and D. Sejdinovic'
collection: publications
preprint: True
permalink: /publication/aodisaggregation
img:
img_width:
excerpt: 'Aerosol-cloud interactions constitute the largest source of uncertainty in assessments of the anthropogenic climate change. This uncertainty arises in part from the difficulty in measuring the vertical distributions of aerosols, and only sporadic vertically resolved observations are available'
date: 2022-05-23
venue:
paperurl:
citation:
---


<center>
  <p align="center">
    <img src="/images/aodisaggregation.png" alt="figure" width="700"/>
  </p>
</center>


Aerosol-cloud interactions constitute the largest source of uncertainty in assessments of the anthropogenic climate change. This uncertainty arises in part from the difficulty in measuring the vertical distributions of aerosols, and only sporadic vertically resolved observations are available. We often have to settle for less informative vertically aggregated proxies such as aerosol optical depth (AOD). In this work, we develop a framework for the vertical disaggregation of AOD into extinction profiles, i.e. the measure of light extinction throughout an atmospheric column, using readily available vertically resolved meteorological predictors such as temperature, pressure or relative humidity. Using Bayesian nonparametric modelling, we devise a simple Gaussian process prior over aerosol vertical profiles and update it with AOD observations to infer a distribution over vertical extinction profiles. To validate our approach, we use ECHAM-HAM aerosol-climate model data which offers self-consistent simulations of meteorological covariates, AOD and extinction profiles. Our results show that, while very simple, our model is able to reconstruct realistic extinction profiles with well-calibrated uncertainty, outperforming by an order of magnitude the idealized baseline which is typically used in satellite AOD retrieval algorithms. In particular, the model demonstrates a faithful reconstruction of extinction patterns arising from aerosol water uptake in the boundary layer. Observations however suggest that other extinction patterns, due to aerosol mass concentration, particle size and radiative properties, might be more challenging to capture and require additional vertically resolved predictors.


[Download pdf](https://arxiv.org/abs/2205.04296)

[Github](https://github.com/shahineb/aodisaggregation)

```
@article{bouabid2022aodisaggregation,
  title={{AODisaggregation: toward global aerosol vertical profiles}},
  author={Bouabid, Shahine and Watson-Parris, Duncan and Stefanović, Sofija and Nenes, Athanasios and Sejdinovic, Dino},
  journal={arXiv preprint arXiv:2205.04296},
  year={2022}
}
```
