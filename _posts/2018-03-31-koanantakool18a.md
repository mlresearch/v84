---
title: Communication-Avoiding Optimization Methods for Distributed Massive-Scale Sparse
  Inverse Covariance Estimation
abstract: Across a variety of scientific disciplines, sparse inverse covariance estimation
  is a popular tool for capturing the underlying dependency relationships in multivariate
  data. Unfortunately, most estimators are not scalable enough to handle the sizes
  of modern high-dimensional data sets (often on the order of terabytes), and assume
  Gaussian samples. To address these deficiencies, we introduce HP-CONCORD, a highly
  scalable optimization method for estimating a sparse inverse covariance matrix based
  on a regularized pseudolikelihood framework, without assuming Gaussianity. Our parallel
  proximal gradient method uses a novel communication-avoiding linear algebra algorithm
  and runs across a multi-node cluster with up to 1k nodes (24k cores), achieving
  parallel scalability on problems with up to ≈819 billion parameters (1.28 million
  dimensions); even on a single node, HP-CONCORD demonstrates scalability, outperforming
  a state-of-the-art method. We also use HP-CONCORD to estimate the underlying dependency
  structure of the brain from fMRI data, and use the result to identify functional
  regions automatically. The results show good agreement with a clustering from the
  neuroscience literature.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: koanantakool18a
month: 0
tex_title: Communication-Avoiding Optimization Methods for Distributed Massive-Scale
  Sparse Inverse Covariance Estimation
firstpage: 1376
lastpage: 1386
page: 1376-1386
order: 1376
cycles: false
author:
- given: Penporn
  family: Koanantakool
- given: Alnur
  family: Ali
- given: Ariful
  family: Azad
- given: Aydin
  family: Buluc
- given: Dmitriy
  family: Morozov
- given: Leonid
  family: Oliker
- given: Katherine
  family: Yelick
- given: Sang-Yun
  family: Oh
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
pdf: http://proceedings.mlr.press/v84/koanantakool18a/koanantakool18a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v84/koanantakool18a/koanantakool18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
