---
title: Bootstrapping EM via Power EM and Convergence in the Naive Bayes Model
abstract: We study the convergence properties of the Expectation-Maximization algorithm
  in the Naive Bayes model. We show that EM can get stuck in regions of slow convergence,
  even when the features are binary and i.i.d. conditioning on the class label, and
  even under random (i.e. non worst-case) initialization. In turn, we show that EM
  can be bootstrapped in a pre-training step that computes a good initialization.
  From this initialization we show theoretically and experimentally that EM converges
  exponentially fast to the true model parameters. Our bootstrapping method amounts
  to running the EM algorithm on appropriately centered iterates of small magnitude,
  which as we show corresponds to effectively performing power iteration on the covariance
  matrix of the mixture model, although power iteration is performed under the hood
  by EM itself. As such, we call our bootstrapping approach “power EM.” Specifically
  for the case of two binary features, we show global exponentially fast convergence
  of EM, even without  bootstrapping. Finally, as the Naive Bayes model is quite expressive,
  we show as corollaries of our convergence results that the EM algorithm globally
  converges to the true model parameters for mixtures of two Gaussians, recovering
  recent results of Xu et al.’2016 and Daskalakis et al. 2017.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: daskalakis18a
month: 0
tex_title: Bootstrapping EM via Power EM and Convergence in the Naive Bayes Model
firstpage: 2056
lastpage: 2064
page: 2056-2064
order: 2056
cycles: false
author:
- given: Costis
  family: Daskalakis
- given: Christos
  family: Tzamos
- given: Manolis
  family: Zampetakis
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
pdf: http://proceedings.mlr.press/v84/daskalakis18a/daskalakis18a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v84/daskalakis18a/daskalakis18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
