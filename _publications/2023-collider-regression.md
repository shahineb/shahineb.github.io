---
title: "Returning The Favour: When Regression Benefits from Probabilistic Causal Knowledge"
authors: 'S. Bouabid*, J. Fawkes*, and D. Sejdinovic'
collection: publications
preprint: False
permalink: /publication/returning-the-favour
excerpt:
date: 2023-01-26
venue: 'International Conference on Machine Learning'
paperurl:
citation:
---

<center>
  <p align="center">
    <img src="/images/collider-regression-1.png" alt="figure" width="300"/>
  </p>
</center>


A directed acyclic graph (DAG) provides valuable prior knowledge that is often discarded in regression tasks in machine learning. We show that the independences arising from the presence of collider structures in DAGs provide meaningful inductive biases, which constrain the regression hypothesis space and improve predictive performance. We introduce collider regression, a framework to incorporate probabilistic causal knowledge from a collider in a regression problem. When the hypothesis space is a reproducing kernel Hilbert space, we prove a strictly positive generalisation benefit under mild assumptions and provide closed-form estimators of the empirical risk minimiser. Experiments on synthetic and climate model data demonstrate performance gains of the proposed methodology.


[Download pdf](https://proceedings.mlr.press/v202/bouabid23a/bouabid23a.pdf)

[Github](https://github.com/shahineb/collider-regression)

```
@article{bouabid2023returning,
  title={{Returning The Favour: When Regression Benefits From Probabilistic Causal Knowledge}},
  author={Bouabid, Shahine and Fawkes, Jake and Sejdinovic, Dino},
  journal={International Conference on Machine Learning},
  volume={202},
  pages={2885--2913},
  year={2023}
}
```
