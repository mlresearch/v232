---
title: Replay Buffer with Local Forgetting for Adapting to Local Environment Changes
  in Deep Model-Based Reinforcement Learning
abstract: One of the key behavioral characteristics used in neuroscience to determine
  whether the subject of study—be it a rodent or a human—exhibits model-based learning
  is effective adaptation to local changes in the environment, a particular form of
  adaptivity that is the focus of this work. In reinforcement learning, however, recent
  work has shown that modern deep model-based reinforcement-learning (MBRL) methods
  adapt poorly to local environment changes. An explanation for this mismatch is that
  MBRL methods are typically designed with sample-efficiency on a single task in mind
  and the requirements for effective adaptation are substantially higher, both in
  terms of the learned world model and the planning routine. One particularly challenging
  requirement is that the learned world model has to be sufficiently accurate throughout
  relevant parts of the state-space. This is challenging for deep-learning-based world
  models due to catastrophic forgetting. And while a replay buffer can mitigate the
  effects of catastrophic forgetting, the traditional first-in-first-out replay buffer
  precludes effective adaptation due to maintaining stale data. In this work, we show
  that a conceptually simple variation of this traditional replay buffer is able to
  overcome this limitation. By removing only samples from the buffer from the local
  neighbourhood of the newly observed samples, deep world models can be built that
  maintain their accuracy across the state-space, while also being able to effectively
  adapt to local changes in the reward function. We demonstrate this by applying our
  replay-buffer variation to a deep version of the classical Dyna method, as well
  as to recent methods such as PlaNet and DreamerV2, demonstrating that deep model-based
  methods can adapt effectively as well to local changes in the environment.
year: '2023'
video: https://youtu.be/j9FKnJJFMvs
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rahimi-kalahroudi23a
month: 0
tex_title: Replay Buffer with Local Forgetting for Adapting to Local Environment Changes
  in Deep Model-Based Reinforcement Learning
firstpage: 21
lastpage: 42
page: 21-42
order: 21
cycles: false
bibtex_author: Rahimi-Kalahroudi, Ali and Rajendran, Janarthanan and Momennejad, Ida
  and van Seijen, Harm and Chandar, Sarath
author:
- given: Ali
  family: Rahimi-Kalahroudi
- given: Janarthanan
  family: Rajendran
- given: Ida
  family: Momennejad
- given: Harm
  family: Seijen
  prefix: van
- given: Sarath
  family: Chandar
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
pdf: https://proceedings.mlr.press/v232/rahimi-kalahroudi23a/rahimi-kalahroudi23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
