---
title: 'Batch-Expansion Training: An Efficient Optimization Framework'
abstract: We propose Batch-Expansion Training (BET), a framework for running a batch
  optimizer on a gradually expanding dataset. As opposed to stochastic approaches,
  batches do not need to be resampled i.i.d. at every iteration, thus making BET more
  resource efficient in a distributed setting, and when disk-access is constrained.
  Moreover, BET can be easily paired with most batch optimizers, does not require
  any parameter-tuning, and compares favorably to existing stochastic and batch methods.
  We show that when the batch size grows exponentially with the number of outer iterations,
  BET achieves optimal O (1/epsilon) data-access convergence rate for strongly convex
  objectives. Experiments in parallel and distributed settings show that BET performs
  better than standard batch and stochastic approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: derezinski18b
month: 0
tex_title: 'Batch-Expansion Training: An Efficient Optimization Framework'
firstpage: 736
lastpage: 744
page: 736-744
order: 736
cycles: false
author:
- given: Michal
  family: Derezinski
- given: Dhruv
  family: Mahajan
- given: S. Sathiya
  family: Keerthi
- given: S. V. N.
  family: Vishwanathan
- given: Markus
  family: Weimer
date: 2018-03-31
address: 
publisher: PMLR
container-title: Proceedings of the Twenty-First International Conference on Artficial
  Intelligence and Statistics
volume: '84'
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 3
  - 31
pdf: http://proceedings.mlr.press/v84/derezinski18b/derezinski18b.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v84/derezinski18b/derezinski18b-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
