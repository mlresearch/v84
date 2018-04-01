---
title: Efficient and principled score estimation with Nyström kernel exponential families
abstract: We propose a fast method with statistical guarantees for learning an exponential
  family density model where the natural parameter is in a reproducing kernel Hilbert
  space, and may be infinite dimensional. The model is learned by fitting the derivative
  of the log density, the score, thus avoiding the need to compute a normalization
  constant. We improved the computational efficiency of an earlier solution with a
  low-rank, Nyström-like solution. The new solution retains the consistency and convergence
  rates of the full-rank solution (exactly in Fisher distance, and nearly in other
  distances), with guarantees on the degree of cost and storage reduction. We evaluate
  the method in experiments on density estimation and in the construction of an adaptive
  Hamiltonian Monte Carlo sampler. Compared to an existing score learning approach
  using a denoising autoencoder, our estimator is empirically more data-efficient
  when estimating the score, runs faster, and has fewer parameters (which can be tuned
  in a principled and interpretable way), in addition to providing statistical guarantees.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: sutherland18a
month: 0
tex_title: Efficient and principled score estimation with Nyström kernel exponential
  families
firstpage: 652
lastpage: 660
page: 652-660
order: 652
cycles: false
author:
- given: Dougal
  family: Sutherland
- given: Heiko
  family: Strathmann
- given: Michael
  family: Arbel
- given: Arthur
  family: Gretton
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
pdf: http://proceedings.mlr.press/v84/sutherland18a/sutherland18a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v84/sutherland18a/sutherland18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
