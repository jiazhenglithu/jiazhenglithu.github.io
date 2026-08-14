---
title: "QuestA: Expanding Reasoning Capacity in LLMs via Question Augmentation"
collection: publications
date: 2026-01-01
venue: 'ICLR'
arxiv: https://arxiv.org/abs/2507.13266
code: https://github.com/foreverlasting1202/QuestA
authors:
  - name: "Jiazheng Li"
    url: "https://jiazhenglithu.github.io"
    highlight: true
  - name: "Hongzhou Lin"
  - name: "Hong Lu"
  - name: "Kaiyue Wen"
  - name: "Zaiwen Yang"
  - name: "Jiaxuan Gao"
  - name: "Yi Wu"
  - name: "Jingzhao Zhang"
abstract: >
  Reinforcement learning (RL) has emerged as a central paradigm for training large language models
  (LLMs) in reasoning tasks. Yet recent studies question RL's ability to incentivize reasoning
  capacity beyond the base model. This raises a key challenge: how can RL be adapted to solve harder
  reasoning problems more effectively? To address this challenge, we propose a simple yet effective
  strategy via Question Augmentation: introduce partial solutions during training to reduce problem
  difficulty and provide more informative learning signals. Our method, QuestA, when applied during
  RL training on math reasoning tasks, not only improves pass@1 but also pass@k—particularly on
  problems where standard RL struggles to make progress. This enables continual improvement over
  strong open-source models such as DeepScaleR and OpenMath Nemotron, further enhancing their
  reasoning capabilities. We achieve new state-of-the-art results on math benchmarks using
  1.5B-parameter models: 72.50% (+10.73%) on AIME24, 62.29% (+12.79%) on AIME25, and 41.67%
  (+10.11%) on HMMT25.
---
