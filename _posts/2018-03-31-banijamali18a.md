---
title: Robust Locally-Linear Controllable Embedding
abstract: 'Embed-to-control (E2C) is a model for solving high-dimensional optimal
  control problems by combining variational auto-encoders with locally-optimal controllers.
  However, the E2C model suffers from two major drawbacks:  1) its objective function
  does not correspond to the likelihood of the data sequence and  2) the variational
  encoder used for embedding typically has large variational approximation error,
  especially when there is noise in the system dynamics. In this paper, we present
  a new model for learning robust locally-linear controllable embedding (RCE). Our
  model directly estimates the predictive conditional density of the future observation
  given the current one, while introducing the bottleneck between the current and
  future observations. Although the bottleneck provides a natural embedding candidate
  for control, our RCE model introduces additional specific structures in the generative
  graphical model so that the model dynamics can be robustly linearized. We also propose
  a principled variational approximation of the embedding posterior that takes the
  future observation into account, and thus, makes the variational approximation more
  robust against the noise. Experimental results show that RCE outperforms the E2C
  model, and does so significantly when the underlying dynamics is noisy.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: banijamali18a
month: 0
tex_title: Robust Locally-Linear Controllable Embedding
firstpage: 1751
lastpage: 1759
page: 1751-1759
order: 1751
cycles: false
author:
- given: Ershad
  family: Banijamali
- given: Rui
  family: Shu
- given: mohammad
  family: Ghavamzadeh
- given: Hung
  family: Bui
- given: Ali
  family: Ghodsi
date: 2018-03-31
address: 
publisher: PMLR
container-title: Proceedings of the Twenty-First International Conference on Artificial
  Intelligence and Statistics
volume: '84'
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 3
  - 31
pdf: http://proceedings.mlr.press/v84/banijamali18a/banijamali18a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v84/banijamali18a/banijamali18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
