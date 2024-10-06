---
title: 'Domain Generalisation via Imprecise Learning'
authors: 'A. Singh, S. L. Chau, S. Bouabid, and K. Muandet'
collection: publications
preprint: False
permalink: /publication/imprecise-domain-generalisation
img:
img_width:
date: 2024-07-27
venue: 'Advances in Neural Information Processing Systems'
paperurl:
citation:
---


Refining low-resolution (LR) spatial fields with high-resolution (HR) information, often known as statistical downscaling, is challenging as the diversity of spatial datasets often prevents direct matching of observations. Yet, when LR samples are modeled as aggregate conditional means of HR samples with respect to a mediating variable that is globally observed, the recovery of the underlying fine-grained field can be framed as taking an "inverse" of the conditional expectation, namely a deconditioning problem. In this work, we propose a Bayesian formulation of deconditioning which naturally recovers the initial reproducing kernel Hilbert space formulation from Hsu and Ramos (2019). We extend deconditioning to a downscaling setup and devise efficient conditional mean embedding estimator for multiresolution data. By treating conditional expectations as inter-domain features of the underlying field, a posterior for the latent field can be established as a solution to the deconditioning problem. Furthermore, we show that this solution can be viewed as a two-staged vector-valued kernel ridge regressor and show that it has a minimax optimal convergence rate under mild assumptions. Lastly, we demonstrate its proficiency in a synthetic and
a real-world atmospheric field downscaling problem, showing substantial improvements over existing methods.


[Download pdf](https://proceedings.mlr.press/v235/singh24a.html)

[Github](https://github.com/muandet-lab/dgil)



```

@article{singh2024domain,
  title={{Domain Generalisation via Imprecise Learning}},
  author={Singh, Anurag and Chau, Siu Lun and Bouabid, Shahine and Muandet, Krikamol},
  journal={Proceedings of the 41st International Conference on Machine Learning},
  volume={235},
  pages={45544--45570},
  year={2024}
}
```