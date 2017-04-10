---
title: Random Consensus Robust PCA
abstract: 'This paper presents R2PCA, a random consensus method for robust principal
  component analysis. R2PCA takes RANSAC’s principle of using as little data as possible
  one step further. It iteratively selects small subsets of the data to identify pieces
  of the principal components, to then stitch them together. We show that if the principal
  components are in general position and the errors are sufficiently sparse, R2PCA
  will exactly recover the principal components with probability 1, in lieu of assumptions
  on coherence or the distribution of the sparse errors, and even under adversarial
  settings. R2PCA enjoys many advantages: it works well under noise, its computational
  complexity scales linearly in the ambient dimension, it is easily parallelizable,
  and due to its low sample complexity, it can be used in settings where data is so
  large it cannot even be stored in memory. We complement our theoretical findings
  with synthetic and real data experiments showing that r2pca outperforms state-of-the-art
  methods in a broad range of settings.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: pimentel-alarcon17a
month: 0
tex_title: "{Random Consensus Robust PCA}"
firstpage: 344
lastpage: 352
page: 344-352
order: 344
cycles: false
author:
- given: Daniel
  family: Pimentel-Alarcon
- given: Robert
  family: Nowak
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
pdf: http://proceedings.mlr.press/v54/pimentel-alarcon17a/pimentel-alarcon17a.pdf
extras:
- label: Supplementary pdf
  link: http://proceedings.mlr.press/v54/pimentel-alarcon17a/pimentel-alarcon17a/pimentel-alarcon17a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
