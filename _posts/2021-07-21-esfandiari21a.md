---
title: Adaptivity in Adaptive Submodularity
abstract: Adaptive sequential decision making is one of the central challenges in
  machine learning and artificial intelligence. In such problems, the goal is to design
  an interactive policy that plans for an action to take, from a finite set of $n$
  actions, given some partial observations. It has been shown that in many applications
  such as active learning, robotics, sequential experimental design, and active detection,
  the utility function satisfies adaptive submodularity, a notion that generalizes
  the notion of diminishing returns to policies.  In this paper, we revisit the power
  of adaptivity in maximizing an adaptive monotone submodular function. We propose
  an efficient semi adaptive policy that with $O(\log n \times\log k)$ adaptive rounds
  of observations can achieve an almost tight $1-1/e-\eps$ approximation guarantee
  with respect to an optimal policy that carries out $k$ actions in a fully sequential
  manner. To complement our results, we also show that it is impossible to achieve
  a constant factor approximation with $o(\log n)$ adaptive rounds. We also extend
  our result to the case of adaptive stochastic minimum cost coverage where the goal
  is to reach a desired utility $Q$ with the cheapest policy. We first prove the long-standing
  conjecture by Golovin and Krause and show that the greedy policy achieves the asymptotically
  tight logarithmic approximation guarantee. We then propose a semi adaptive policy
  that provides the same guarantee in polylogarithmic adaptive rounds through a similar
  information-parallelism scheme. Our results shrink the adaptivity gap in adaptive
  submodular maximization by an exponential factor.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: esfandiari21a
month: 0
tex_title: Adaptivity in Adaptive Submodularity
firstpage: 1823
lastpage: 1846
page: 1823-1846
order: 1823
cycles: false
bibtex_author: Esfandiari, Hossein and Karbasi, Amin and Mirrokni, Vahab
author:
- given: Hossein
  family: Esfandiari
- given: Amin
  family: Karbasi
- given: Vahab
  family: Mirrokni
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
pdf: http://proceedings.mlr.press/v134/esfandiari21a/esfandiari21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
