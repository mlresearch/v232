---
title: Improving Online Continual Learning Performance and Stability with Temporal
  Ensembles
abstract: Neural networks are very effective when trained on large datasets for a
  large number of iterations. However, when they are trained on non-stationary streams
  of data and in an online fashion, their performance is reduced (1) by the online
  setup, which limits the availability of data, (2) due to catastrophic forgetting
  because of the non-stationary nature of the data. Furthermore, several recent works
  (Caccia et al. 2022, Lange et al. 2023) showed that replay methods used in continual
  learning suffer from the \textit{stability gap}, encountered when evaluating the
  model continually (rather than only on task boundaries). In this article, we study
  the effect of model ensembling as a way to improve performance and stability in
  online continual learning. We notice that naively ensembling models coming from
  a variety of training tasks increases the performance in online continual learning
  considerably. Starting from this observation, and drawing inspirations from semi-supervised
  learning ensembling methods, we use a lightweight temporal ensemble that computes
  the exponential moving average of the weights (EMA) at test time, and show that
  it can drastically increase the performance and stability when used in combination
  with several methods from the literature.
year: '2023'
video: https://youtu.be/YbiZHIs9sfw
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: soutif-cormerais23a
month: 0
tex_title: Improving Online Continual Learning Performance and Stability with Temporal
  Ensembles
firstpage: 828
lastpage: 845
page: 828-845
order: 828
cycles: false
bibtex_author: Soutif--Cormerais, Albin and Carta, Antonio and van de Weijer, Joost
author:
- given: Albin
  family: Soutif–Cormerais
- given: Antonio
  family: Carta
- given: Joost
  family: Weijer
  prefix: van de
date: 2023-11-20
address:
container-title: Proceedings of The 2nd Conference on Lifelong Learning Agents
volume: '232'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 11
  - 20
pdf: https://proceedings.mlr.press/v232/soutif-cormerais23a/soutif-cormerais23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
