---
title: "Returning The Favour: When Regression Benefits from Probabilistic Causal Knowledge"
authors: 'S. Bouabid*, J. Fawkes*, and D. Sejdinovic'
collection: publications
preprint: True
permalink: /publication/returning-the-favour
excerpt: 'A directed acyclic graph (DAG) provides valuable prior knowledge that is often discarded in regression tasks in machine learning. We show that the independences arising from the presence of collider structures in DAGs provide meaningful inductive biases,'
date: 2023-01-26
venue:
paperurl:
citation:
---

<center>
  <p align="center">
    <img src="/images/collider-regression-1.png" alt="figure" width="300"/>
  </p>
</center>


A directed acyclic graph (DAG) provides valuable prior knowledge that is often discarded in regression tasks in machine learning. We show that the independences arising from the presence of collider structures in DAGs provide meaningful inductive biases, which constrain the regression hypothesis space and improve predictive performance. We introduce collider regression, a framework to incorporate probabilistic causal knowledge from a collider in a regression problem. When the hypothesis space is a reproducing kernel Hilbert space, we prove a strictly positive generalisation benefit under mild assumptions and provide closed-form estimators of the empirical risk minimiser. Experiments on synthetic and climate model data demonstrate performance gains of the proposed methodology.


[Download pdf](https://arxiv.org/abs/2301.11214)

[Github](https://github.com/shahineb/collide-regression)

```
@article{bouabid2023returning,
  title={Returning The Favour: When Regression Benefits From Probabilistic Causal Knowledge},
  author={Bouabid, Shahine and Fawkes, Jake and Sejdinovic, Dino},
  journal={arXiv preprint arXiv:2301.11214},
  year={2023}
}
```
