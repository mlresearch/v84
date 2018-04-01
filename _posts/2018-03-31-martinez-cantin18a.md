---
title: Practical Bayesian optimization in the presence of outliers
abstract: 'Inference in the presence of outliers is an important field of research
  as outliers are ubiquitous and may arise across a variety of problems and domains.
  Bayesian optimization is method that heavily relies on probabilistic inference.
  This allows outstanding sample efficiency because the probabilistic machinery provides
  a memory of the whole optimization process. However, that virtue becomes a disadvantage
  when the memory is populated with outliers, inducing bias in the estimation. In
  this paper, we present an empirical evaluation of Bayesian optimization methods
  in the presence of outliers. The empirical evidence shows that Bayesian optimization
  with robust regression often produces suboptimal results. We then propose a new
  algorithm which combines robust regression (a Gaussian process with Student-t likelihood)
  with outlier diagnostics to classify data points as outliers or inliers. By using
  an scheduler for the classification of outliers, our method is more efficient and
  has better convergence over the standard robust regression. Furthermore, we show
  that even in controlled situations with no expected outliers, our method is able
  to produce better results. '
layout: inproceedings
series: Proceedings of Machine Learning Research
id: martinez-cantin18a
month: 0
tex_title: Practical Bayesian optimization in the presence of outliers
firstpage: 1722
lastpage: 1731
page: 1722-1731
order: 1722
cycles: false
author:
- given: Ruben
  family: Martinez-Cantin
- given: Kevin
  family: Tee
- given: Michael
  family: McCourt
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
pdf: http://proceedings.mlr.press/v84/martinez-cantin18a/martinez-cantin18a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
