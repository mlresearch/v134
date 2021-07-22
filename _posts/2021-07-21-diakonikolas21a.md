---
title: The Sample Complexity of Robust Covariance Testing
abstract: We study the problem of testing the covariance matrix of a high-dimensional
  Gaussian in a robust setting, where the input distribution has been corrupted in
  Huber’s contamination model. Specifically, we are given i.i.d. samples from a distribution
  of the form $Z = (1-\epsilon) X + \epsilon B$, where $X$ is a zero-mean and unknown covariance
  Gaussian $\mathcal{N}(0, \Sigma)$, $B$ is a fixed but unknown noise distribution,
  and $\epsilon>0$ is an arbitrarily small constant representing the proportion of contamination.  We
  want to distinguish between the cases that $\Sigma$ is the identity matrix versus
  $\gamma$-far from the identity in Frobenius norm.  In the absence of contamination,
  prior work gave a simple tester for this hypothesis testing task that uses $O(d)$
  samples. Moreover, this sample upper bound was shown to be best possible, within
  constant factors. Our main result is that the sample complexity of covariance testing
  dramatically increases in the contaminated setting. In particular, we prove a sample
  complexity lower bound of $\Omega(d^2)$ for $\epsilon$ an arbitrarily small constant
  and $\gamma = 1/2$.  This lower bound is best possible, as $O(d^2)$ samples suffice
  to even robustly {\em learn} the covariance. The conceptual implication of our result
  is that, for the natural setting we consider, robust hypothesis testing is at least
  as hard as robust estimation.
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
bibtex_author: Diakonikolas, Ilias and Kane, Daniel M.
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel M.
  family: Kane
date: 2021-07-21
address:
container-title: Proceedings of Thirty Fourth Conference on Learning Theory
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
