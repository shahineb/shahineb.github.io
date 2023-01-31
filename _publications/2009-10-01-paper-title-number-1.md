---
title: 'Deconditional Downscaling with Gaussian processes'
collection: publications
permalink: /publication/deconditional-downscaling
img: /images/deconditional-downscaling.png
excerpt: ''
date: 2021-05-27
venue: 'Advances in Neural Information Processing Systems'
paperurl:
citation:
---
Refining low-resolution (LR) spatial fields with high-resolution (HR) information, often known as statistical downscaling, is challenging as the diversity of spatial datasets often prevents direct matching of observations. Yet, when LR samples are modeled as aggregate conditional means of HR samples with respect to a mediating variable that is globally observed, the recovery of the underlying fine-grained field can be framed as taking an "inverse" of the conditional expectation, namely a deconditioning problem. In this work, we propose a Bayesian formulation of deconditioning which naturally recovers the initial reproducing kernel Hilbert space formulation from Hsu and Ramos (2019). We extend deconditioning to a downscaling setup and devise efficient conditional mean embedding estimator for multiresolution data. By treating conditional expectations as inter-domain features of the underlying field, a posterior for the latent field can be established as a solution to the deconditioning problem. Furthermore, we show that this solution can be viewed as a two-staged vector-valued kernel ridge regressor and show that it has a minimax optimal convergence rate under mild assumptions. Lastly, we demonstrate its proficiency in a synthetic and a real-world atmospheric field downscaling problem, showing substantial improvements over existing methods.

[Download pdf](https://proceedings.neurips.cc/paper/2021/file/94aef38441efa3380a3bed3faf1f9d5d-Paper.pdf)
[Github repo](https://github.com/shahineb/deconditional-downscaling)

```
@article{chau2021deconditional,
         title={Deconditional downscaling with gaussian processes},
         author={Chau, Siu Lun and Bouabid, Shahine and Sejdinovic, Dino},
         journal={Advances in Neural Information Processing Systems},
         volume={34}, pages={17813--17825},
         year={2021}
```
