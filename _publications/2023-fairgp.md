---
title: "FaIRGP: A Bayesian Energy Balance Model for Surface Temperatures Emulation"
authors: 'S. Bouabid, D. Sejdinovic and D. Watson-Parris'
collection: publications
preprint: False
permalink: /publication/fairgp
excerpt:
date: 2024-06-07
venue: 'Journal of Advances in Modeling Earth Systems'
paperurl:
citation:
---


<center>
  <p align="center">
    <img src="/images/fairgp-logo.png" alt="figure" width="400"/>
  </p>
</center>


Emulators, or reduced complexity climate models, are surrogate Earth system models (ESMs) that produce projections of key climate quantities with minimal computational resources. Using time-series modeling or more advanced machine learning techniques, data-driven emulators have emerged as a promising avenue of research, producing spatially resolved climate responses that are visually indistinguishable from state-of-the-art ESMs. Yet, their lack of physical interpretability limits their wider adoption. In this work, we introduce FaIRGP, a data-driven emulator that satisfies the physical temperature response equations of an energy balance model. The result is an emulator that (a) enjoys the flexibility of statistical machine learning models and can learn from data, and (b) has a robust physical grounding with interpretable parameters that can be used to make inference about the climate system. Further, our Bayesian approach allows a principled and mathematically tractable uncertainty quantification. Our model demonstrates skillful emulation of global mean surface temperature and spatial surface temperatures across realistic future scenarios. Its ability to learn from data allows it to outperform EBMs, while its robust physical foundation safeguards against the pitfalls of purely data-driven models. We also illustrate how FaIRGP can be used to obtain estimates of top-of-atmosphere radiative forcing and discuss the benefits of its mathematical tractability for applications such as detection and attribution or precipitation emulation. We hope that this work will contribute to widening the adoption of data-driven methods in climate emulation.


[Download pdf](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023MS003926)

[Github](https://github.com/shahineb/fairgp)

```
@article{bouabid2024fairgp,
  title={FaIRGP: A Bayesian Energy Balance Model for Surface Temperatures Emulation},
  author={Bouabid, Shahine and Sejdinovic, Dino and Watson-Parris, Duncan},
  journal={Journal of Advances in Modeling Earth Systems},
  volume={16},
  number={6},
  pages={e2023MS003926},
  year={2024},
  publisher={Wiley Online Library}
}
```
