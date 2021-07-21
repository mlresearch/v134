---
title: Sparse sketches with small inversion bias
abstract: "For a tall $n\\times d$ matrix $A$ and a random\r $m\\times n$ sketching
  matrix $S$, the sketched\r estimate of the inverse covariance matrix $(A^\\top\r
  A)^{-1}$ is typically biased: $E[(\\tilde\r A^\\top\\tilde A)^{-1}]\\ne(A^\\top
  A)^{-1}$, where\r $\\tilde A=SA$. This phenomenon, which we call\r inversion bias,
  arises, e.g., in statistics and\r distributed optimization, when averaging multiple\r
  independently constructed estimates of quantities\r that depend on the inverse covariance.
  We develop a\r framework for analyzing inversion bias, based on our\r proposed concept
  of an $(\\epsilon,\\delta)$-unbiased\r estimator for random matrices. We show that
  when the\r sketching matrix $S$ is dense and has\r i.i.d. sub-gaussian entries,
  then after simple\r rescaling, the estimator $(\\frac m{m-d}\\tilde\r A^\\top\\tilde
  A)^{-1}$ is\r $(\\epsilon,\\delta)$-unbiased for $(A^\\top A)^{-1}$\r with a sketch
  of size $m=O(d+\\sqrt\r d/\\epsilon)$. This implies that for $m=O(d)$, the\r inversion
  bias of this estimator is $O(1/\\sqrt d)$,\r which is much smaller than the $\\Theta(1)$\r
  approximation error obtained as a consequence of the\r subspace embedding guarantee
  for sub-gaussian\r sketches. We then propose a new sketching technique,\r called
  LEverage Score Sparsified (LESS) embeddings,\r which uses ideas from both data-oblivious
  sparse\r embeddings as well as data-aware leverage-based row\r sampling methods,
  to get $\\epsilon$ inversion bias\r for sketch size $m=O(d\\log d+\\sqrt d/\\epsilon)$
  in\r time $O(\\text{nnz}(A)\\log n+md^2)$, where nnz is the\r number of non-zeros.
  The key techniques enabling our\r analysis include an extension of a classical\r
  inequality of Bai and Silverstein for random\r quadratic forms, which we call the
  Restricted\r Bai-Silverstein inequality; and anti-concentration\r of the Binomial
  distribution via the Paley-Zygmund\r inequality, which we use to prove a lower bound\r
  showing that leverage score sampling sketches\r generally do not achieve small inversion
  bias."
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
container-title: "Proceedings of Thirty Fourth Conference on Learning\r Theory"
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
