---
title: Label Filters for Large Scale Multilabel Classification
abstract: When assigning labels to a test instance, most multilabel and multiclass
  classifiers systematically evaluate every single label to decide whether it is relevant
  or not. This linear scan over labels becomes prohibitive when the number of labels
  is very large. To alleviate this problem we propose a two step approach where computationally
  efficient label filters pre-select a small set of candidate labels before the base
  multiclass or multilabel classifier is applied. The label filters select candidate
  labels by projecting a test instance on a filtering line, and retaining only the
  labels that have training instances in the vicinity of this projection.  The filter
  parameters are learned directly from data by solving a constraint optimization problem,
  and are independent of the base multilabel classifier. The proposed label filters
  can be used in conjunction with any multiclass or multilabel classifier that requires
  a linear scan over the labels, and speed up prediction by orders of magnitude without
  significant impact on performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: niculescu-mizil17a
month: 0
tex_title: "{Label Filters for Large Scale Multilabel Classification}"
firstpage: 1448
lastpage: 1457
page: 1448-1457
order: 1448
cycles: false
author:
- given: Alexandru
  family: Niculescu-Mizil
- given: Ehsan
  family: Abbasnejad
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
pdf: http://proceedings.mlr.press/v54/niculescu-mizil17a/niculescu-mizil17a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
