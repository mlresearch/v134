---
title: The Sample Complexity of Robust Covariance Testing
abstract: "We study the problem of testing the covariance\r matrix of a high-dimensional
  Gaussian in a robust\r setting, where the input distribution has been\r corrupted
  in Huber’s contamination model.\r Specifically, we are given i.i.d. samples from
  a\r distribution of the form $Z = (1-\\eps) X + \\eps B$,\r where $X$ is a zero-mean
  and unknown covariance\r Gaussian $\\mathcal{N}(0, \\Sigma)$, $B$ is a fixed\r but
  unknown noise distribution, and $\\eps>0$ is an\r arbitrarily small constant representing
  the\r proportion of contamination.  We want to distinguish\r between the cases that
  $\\Sigma$ is the identity\r matrix versus $\\gamma$-far from the identity in\r Frobenius
  norm.  In the absence of contamination,\r prior work gave a simple tester for this
  hypothesis\r testing task that uses $O(d)$ samples. Moreover,\r this sample upper
  bound was shown to be best\r possible, within constant factors. Our main result\r
  is that the sample complexity of covariance testing\r dramatically increases in
  the contaminated\r setting. In particular, we prove a sample complexity\r lower
  bound of $\\Omega(d^2)$ for $\\eps$ an\r arbitrarily small constant and $\\gamma
  = 1/2$.  This\r lower bound is best possible, as $O(d^2)$ samples\r suffice to even
  robustly {\\em learn} the\r covariance. The conceptual implication of our result\r
  is that, for the natural setting we consider, robust\r hypothesis testing is at
  least as hard as robust\r estimation."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas21a
month: 0
tex_title: The Sample Complexity of Robust Covariance Testing
firstpage: 1511
lastpage: 1521
page: 1511-1521
order: 1511
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel M
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel M
  family: Kane
date: 2021-07-21
address:
container-title: "Proceedings of Thirty Fourth Conference on Learning\r Theory"
volume: '134'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 7
  - 21
pdf: http://proceedings.mlr.press/v134/diakonikolas21a/diakonikolas21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
