---
title: Hierarchical Representation Learning for Markov Decision Processes
abstract: In this paper, we present a novel method for learning reward-agnostic hierarchical
  representations of Markov Decision Processes. Our method works by partitioning the
  state space into subsets, and defines subtasks for performing transitions between
  the partitions. At the high level, we use model-based planning to decide which subtask
  to pursue next from a given partition. We formulate the problem of partitioning
  the state space as an optimization problem that can be solved using gradient descent
  given a set of sampled trajectories, making our method suitable for high-dimensional
  problems with large state spaces. We empirically validate the method, by showing
  that it can successfully learn useful hierarchical representations in domains with
  high-dimensional states. Once learned, the hierarchical representation can be used
  to solve different tasks in the given domain, thus generalizing knowledge across
  tasks.
year: '2023'
video: https://youtu.be/1DZ79Ql1Fnc
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: steccanella23a
month: 0
tex_title: Hierarchical Representation Learning for Markov Decision Processes
firstpage: 568
lastpage: 585
page: 568-585
order: 568
cycles: false
bibtex_author: Steccanella, Lorenzo and Totaro, Simone and Jonsson, Anders
author:
- given: Lorenzo
  family: Steccanella
- given: Simone
  family: Totaro
- given: Anders
  family: Jonsson
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
pdf: https://proceedings.mlr.press/v232/steccanella23a/steccanella23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
