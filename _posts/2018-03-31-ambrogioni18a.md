---
title: 'Integral Transforms from Finite Data: An Application of Gaussian Process Regression
  to Fourier Analysis'
abstract: 'Computing accurate estimates of the Fourier transform of analog signals
  from discrete data points is important in many fields of science and engineering.
  The conventional approach of performing the discrete Fourier transform of the data
  implicitly assumes periodicity and bandlimitedness of the signal. In this paper,
  we use Gaussian process regression to estimate the Fourier transform (or any other
  integral transform) without making these assumptions. This is possible because the
  posterior expectation of Gaussian process regression maps a finite set of samples
  to a function defined on the whole real line, expressed as a linear combination
  of covariance functions. We estimate the covariance function from the data using
  an appropriately designed gradient ascent method that constrains the solution to
  a linear combination of tractable kernel functions. This procedure results in a
  posterior expectation of the analog signal whose Fourier transform can be obtained
  analytically by exploiting linearity. Our simulations show that the new method leads
  to sharper and more precise estimation of the spectral density both in noise-free
  and noise-corrupted signals. We further validate the method in two real-world applications:
  the analysis of the yearly fluctuation in atmospheric CO2 level and the analysis
  of the spectral content of brain signals.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: ambrogioni18a
month: 0
tex_title: 'Integral Transforms from Finite Data: An Application of Gaussian Process
  Regression to Fourier Analysis'
firstpage: 217
lastpage: 225
page: 217-225
order: 217
cycles: false
author:
- given: Luca
  family: Ambrogioni
- given: Eric
  family: Maris
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
pdf: http://proceedings.mlr.press/v84/ambrogioni18a/ambrogioni18a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
