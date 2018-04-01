---
title: Subsampling for Ridge Regression via Regularized Volume Sampling
abstract: Given n vectors $x_i ∈R^d$, we want to fit a linear regression model for
  noisy labels $y_i ∈\mathbb{R}$.  The ridge estimator is a classical solution to
  this problem. However, when labels are expensive, we are forced to select only a
  small subset of vectors $x_i$ for which we obtain the labels $y_i$. We propose a
  new procedure for selecting the subset of vectors, such that the ridge estimator
  obtained from that subset offers strong statistical guarantees in terms of the mean
  squared prediction error over the entire dataset of n labeled vectors. The number
  of labels needed is proportional to the statistical dimension of the problem which
  is often much smaller than d. Our method is an extension of a joint subsampling
  procedure called volume sampling. A second major contribution is that we speed up
  volume sampling so that it is essentially as efficient as leverage scores, which
  is the main i.i.d. subsampling procedure for this task. Finally, we show theoretically
  and experimentally that volume sampling has a clear advantage over any i.i.d. sampling
  when labels are expensive.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: derezinski18a
month: 0
tex_title: Subsampling for Ridge Regression via Regularized Volume Sampling
firstpage: 716
lastpage: 725
page: 716-725
order: 716
cycles: false
author:
- given: Michal
  family: Derezinski
- given: Manfred
  family: Warmuth
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
pdf: http://proceedings.mlr.press/v84/derezinski18a/derezinski18a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v84/derezinski18a/derezinski18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
