---
title: "Beyond Data Schedule: Fast LLM Pretraining on Data Mixtures by Loss-Reweighting"
collection: publications
date: 2026-10-23
venue: 'arXiv preprint'
arxiv: https://arxiv.org/abs/2610.32141
authors:
  - name: "Jiazheng Li"
    url: "https://jiazhenglithu.github.io"
    highlight: true
  - name: "Huaqing Zhang"
  - name: "Jing Xu"
    url: "https://jingxuthu.github.io/"
  - name: "Tianle Cai"
  - name: "Jingzhao Zhang"
    url: "https://sites.google.com/view/jingzhao/home"
abstract: >
  Multi-stage LLM pretraining can improve specialized capabilities while eroding earlier knowledge.
  We study domain loss weights as a separate control from data-mixture ratios, keeping each domain's
  training exposure fixed. Controlled experiments show that loss reweighting can yield a single
  checkpoint with stronger knowledge and reasoning performance than either training stage's best
  checkpoint. Our method, LARE (Loss-Adaptive Reweighting under fixed Exposure), uses running loss
  statistics and a normalized inverse-square-root rule motivated by gradient-noise analysis to adapt
  domain weights without changing the sampled mixture or searching over additional training runs.
  On a 1.5B model trained for 240B tokens across knowledge, mathematics, and code, LARE improves
  all five evaluated benchmarks over a matched direct mixture, with an average gain of 7.84
  percentage points.
---
