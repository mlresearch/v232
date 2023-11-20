---
title: Comparing the Efficacy of Fine-Tuning and Meta-Learning for Few-Shot Policy
  Imitation
abstract: 'In this paper we explore few-shot imitation learning for control problems,
  which involves learning to imitate a target policy by accessing a limited set of
  offline rollouts. This setting has been relatively under-explored despite its relevance
  to robotics and control applications. State-of-the-art methods developed to tackle
  few-shot imitation rely on meta-learning, which is expensive to train as it requires
  access to a distribution over tasks (rollouts from many target policies and variations
  of the base environment). Given this limitation we investigate an alternative approach,
  fine-tuning, a family of methods that pretrain on a single dataset and then fine-tune
  on unseen domain-specific data. Recent work has shown that fine-tuners outperform
  meta-learners in few-shot image classification tasks, especially when the data is
  out-of-domain. Here we evaluate to what extent this is true for control problems,
  proposing a simple yet effective baseline which relies on two stages: (i) training
  a base policy online via reinforcement learning (e.g. Soft Actor-Critic) on a single
  base environment, (ii) fine-tuning the base policy via behavioral cloning on a few
  offline rollouts of the target policy. Despite its simplicity this baseline is competitive
  with meta-learning methods on a variety of conditions and is able to imitate target
  policies trained on unseen variations of the original environment. Importantly,
  the proposed approach is practical and easy to implement, as it does not need any
  complex meta-training protocol. As a further contribution, we release an open source
  dataset called iMuJoCo (iMitation MuJoCo) consisting of 154 variants of popular
  OpenAI-Gym MuJoCo environments with associated pretrained target policies and rollouts,
  which can be used by the community to study few-shot imitation learning and offline
  reinforcement learning.'
year: '2023'
video: https://youtu.be/JPGPRvVac9M
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: patacchiola23a
month: 0
tex_title: Comparing the Efficacy of Fine-Tuning and Meta-Learning for Few-Shot Policy
  Imitation
firstpage: 878
lastpage: 908
page: 878-908
order: 878
cycles: false
bibtex_author: Patacchiola, Massimiliano and Sun, Mingfei and Hofmann, Katja and Turner,
  Richard E.
author:
- given: Massimiliano
  family: Patacchiola
- given: Mingfei
  family: Sun
- given: Katja
  family: Hofmann
- given: Richard E.
  family: Turner
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
pdf: https://proceedings.mlr.press/v232/patacchiola23a/patacchiola23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
