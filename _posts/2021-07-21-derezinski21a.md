---
title: Sparse sketches with small inversion bias
abstract: 'For a tall $n\times d$ matrix $A$ and a random $m\times n$ sketching matrix
  $S$, the sketched estimate of the inverse covariance matrix $(A^\top A)^{-1}$ is
  typically biased: $E[(\tilde A^\top\tilde A)^{-1}]\ne(A^\top A)^{-1}$, where $\tilde
  A=SA$. This phenomenon, which we call inversion bias, arises, e.g., in statistics
  and distributed optimization, when averaging multiple independently constructed
  estimates of quantities that depend on the inverse covariance. We develop a framework
  for analyzing inversion bias, based on our proposed concept of an $(\epsilon,\delta)$-unbiased
  estimator for random matrices. We show that when the sketching matrix $S$ is dense
  and has i.i.d. sub-gaussian entries, then after simple rescaling, the estimator
  $(\frac m{m-d}\tilde A^\top\tilde A)^{-1}$ is $(\epsilon,\delta)$-unbiased for $(A^\top
  A)^{-1}$ with a sketch of size $m=O(d+\sqrt d/\epsilon)$. This implies that for
  $m=O(d)$, the inversion bias of this estimator is $O(1/\sqrt d)$, which is much
  smaller than the $\Theta(1)$ approximation error obtained as a consequence of the
  subspace embedding guarantee for sub-gaussian sketches. We then propose a new sketching
  technique, called LEverage Score Sparsified (LESS) embeddings, which uses ideas
  from both data-oblivious sparse embeddings as well as data-aware leverage-based
  row sampling methods, to get $\epsilon$ inversion bias for sketch size $m=O(d\log
  d+\sqrt d/\epsilon)$ in time $O(\text{nnz}(A)\log n+md^2)$, where nnz is the number
  of non-zeros. The key techniques enabling our analysis include an extension of a
  classical inequality of Bai and Silverstein for random quadratic forms, which we
  call the Restricted Bai-Silverstein inequality; and anti-concentration of the Binomial
  distribution via the Paley-Zygmund inequality, which we use to prove a lower bound
  showing that leverage score sampling sketches generally do not achieve small inversion
  bias.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: derezinski21a
month: 0
tex_title: Sparse sketches with small inversion bias
firstpage: 1467
lastpage: 1510
page: 1467-1510
order: 1467
cycles: false
bibtex_author: Derezinski, Michal and Liao, Zhenyu and Dobriban, Edgar and Mahoney,
  Michael
author:
- given: Michal
  family: Derezinski
- given: Zhenyu
  family: Liao
- given: Edgar
  family: Dobriban
- given: Michael
  family: Mahoney
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
pdf: http://proceedings.mlr.press/v134/derezinski21a/derezinski21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
