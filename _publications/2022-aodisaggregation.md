---
title: "Aerosol optical depth disaggregation: toward global aerosol vertical profiles"
authors: 'S. Bouabid, D. Watson-Parris, S. Stefanovic, A. Nenes, and D. Sejdinovic'
collection: publications
preprint: False
permalink: /publication/aodisaggregation
img:
img_width:
excerpt: ''
date: 2024-09-16
venue: 'Environmental Data Science'
paperurl:
citation:
---


<center>
  <p align="center">
    <img src="/images/aodisaggregation.png" alt="figure" width="700"/>
  </p>
</center>


Aerosol-cloud interactions constitute the largest source of uncertainty in assessments of the anthropogenic climate change. This uncertainty arises in part from the difficulty in measuring the vertical distributions of aerosols, and only sporadic vertically resolved observations are available. We often have to settle for less informative vertically aggregated proxies such as aerosol optical depth (AOD). In this work, we develop a framework for the vertical disaggregation of AOD into extinction profiles, i.e. the measure of light extinction throughout an atmospheric column, using readily available vertically resolved meteorological predictors such as temperature, pressure or relative humidity. Using Bayesian nonparametric modelling, we devise a simple Gaussian process prior over aerosol vertical profiles and update it with AOD observations to infer a distribution over vertical extinction profiles. To validate our approach, we use ECHAM-HAM aerosol-climate model data which offers self-consistent simulations of meteorological covariates, AOD and extinction profiles. Our results show that, while very simple, our model is able to reconstruct realistic extinction profiles with well-calibrated uncertainty, outperforming by an order of magnitude the idealized baseline which is typically used in satellite AOD retrieval algorithms. In particular, the model demonstrates a faithful reconstruction of extinction patterns arising from aerosol water uptake in the boundary layer. Observations however suggest that other extinction patterns, due to aerosol mass concentration, particle size and radiative properties, might be more challenging to capture and require additional vertically resolved predictors.


[Download pdf](https://www.cambridge.org/core/journals/environmental-data-science/article/aerosol-optical-depth-disaggregation-toward-global-aerosol-vertical-profiles/8CCB065837EDC3E2DFA731AA5C73092E)

[Github](https://github.com/shahineb/aodisaggregation)

```
@article{bouabid2024aerosol,
  title={Aerosol optical depth disaggregation: toward global aerosol vertical profiles},
  author={Bouabid, Shahine and Watson-Parris, Duncan and Stefanovi{\'c}, Sofija and Nenes, Athanasios and Sejdinovic, Dino},
  journal={Environmental Data Science},
  volume={3},
  pages={e16},
  year={2024},
  publisher={Cambridge University Press}
}
```
