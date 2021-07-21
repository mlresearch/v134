---
title: Approximation Algorithms for Socially Fair Clustering
abstract: We present an (e^{O(p)} (log \ell) / (log log \ell))-approximation algorithm
  for socially fair clustering with the l_p-objective. In this problem, we are given
  a set of points in a metric space. Each point belongs to one (or several) of \ell
  groups. The goal is to find a k-medians, k-means, or, more generally, l_p-clustering
  that is simultaneously good for all of the groups. More precisely, we need to find
  a set of k centers C so as to minimize the maximum over all groups j of \sum_{u
  in group j} d(u, C)^p.  The socially fair clustering problem was independently proposed
  by Abbasi, Bhaskara, and Venkatasubramanian (2021) and Ghadiri, Samadi, and Vempala
  (2021). Our algorithm improves and generalizes their O(\ell)-approximation algorithms
  for the problem.  The natural LP relaxation for the problem has an integrality gap
  of \Omega(\ell). In order to obtain our result, we introduce a strengthened LP relaxation
  and show that it has an integrality gap of \Theta((log \ell) / (log log \ell)) for
  a fixed p. Additionally, we present a bicriteria approximation algorithm, which
  generalizes the bicriteria approximation of Abbasi et al. (2021).
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: makarychev21a
month: 0
tex_title: Approximation Algorithms for Socially Fair Clustering
firstpage: 3246
lastpage: 3264
page: 3246-3264
order: 3246
cycles: false
bibtex_author: Makarychev, Yury and Vakilian, Ali
author:
- given: Yury
  family: Makarychev
- given: Ali
  family: Vakilian
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
pdf: http://proceedings.mlr.press/v134/makarychev21a/makarychev21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
