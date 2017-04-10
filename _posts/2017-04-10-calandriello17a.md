---
title: Distributed Adaptive Sampling for Kernel Matrix Approximation
abstract: Most kernel-based methods, such as kernel regression, kernel PCA, ICA, or
  $k$-means clustering, do not scale to large datasets, because constructing and storing
  the kernel matrix $K_n$ requires at least $O(n^2)$ time and space for $n$ samples.
  Recent works (Alaoui 2014, Musco 2016) show that sampling points with replacement
  according to their ridge leverage scores (RLS) generates small dictionaries of relevant
  points with strong spectral approximation guarantees for $K_n$. The drawback of
  RLS-based methods is that computing exact RLS requires constructing and storing
  the whole kernel matrix. In this paper, we introduce SQUEAK, a new algorithm for
  kernel approximation based on RLS sampling that \emphsequentially processes the
  dataset, storing a dictionary which creates accurate kernel matrix approximations
  with a number of points that only depends on the effective dimension $d_eff(γ)$
  of the dataset. Moreover since all the RLS estimations are efficiently performed
  using only the small dictionary, SQUEAK never constructs the whole matrix $K_n$,
  runs in linear time $\widetildeO(nd_eff(γ)^3)$ w.r.t. $n$, and requires only a single
  pass over the dataset. We also propose a parallel and distributed version of SQUEAK
  achieving similar accuracy in as little as $\widetildeO(\log(n)d_eff(γ)^3)$ time.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: calandriello17a
month: 0
tex_title: "{Distributed Adaptive Sampling for Kernel Matrix Approximation}"
firstpage: 1421
lastpage: 1429
page: 1421-1429
order: 1421
cycles: false
author:
- given: Daniele
  family: Calandriello
- given: Alessandro
  family: Lazaric
- given: Michal
  family: Valko
date: 2017-04-10
address: 
publisher: PMLR
container-title: Proceedings of the 20th International Conference on Artificial Intelligence
  and Statistics
volume: '54'
genre: inproceedings
issued:
  date-parts:
  - 2017
  - 4
  - 10
pdf: http://proceedings.mlr.press/v54/calandriello17a/calandriello17a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v54/calandriello17a/calandriello17a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
