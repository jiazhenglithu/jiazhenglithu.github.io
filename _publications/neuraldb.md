---
title: "NeuralDB: Scaling Knowledge Editing in LLMs to 100,000 Facts with Neural KV Database"
collection: publications
date: 2026-01-01
venue: 'ICLR'
arxiv: https://arxiv.org/abs/2507.18028
authors:
  - name: "Weizhi Fei"
  - name: "Hao Shi"
  - name: "Jing Xu"
  - name: "Jingchen Peng"
  - name: "Jiazheng Li"
    url: "https://jiazhenglithu.github.io"
    highlight: true
  - name: "Jingzhao Zhang"
  - name: "Bo Bai"
  - name: "Wei Han"
  - name: "Zhenyuan Chen"
  - name: "Xueyan Niu"
abstract: >
  Efficiently editing knowledge stored in large language models (LLMs) enables model updates without
  large-scale training. One possible solution is Locate-and-Edit (L&E), allowing simultaneous
  modifications of a massive number of facts. However, such editing may compromise the general
  abilities of LLMs and even result in forgetting edited facts when scaling up to thousands of edits.
  In this paper, we model existing linear L&E methods as querying a Key-Value (KV) database. From
  this perspective, we then propose NeuralDB, an editing framework that explicitly represents the
  edited facts as a neural KV database equipped with a non-linear gated retrieval module, effectively
  preserving the general abilities of LLMs. Comprehensive experiments involving the editing of 10,000
  facts were conducted on the ZsRE and CounterFacts datasets, using GPT2-XL, GPT-J (6B) and Llama-3
  (8B). The results demonstrate that NeuralDB not only excels in editing efficacy, generalization,
  specificity, fluency, and consistency, but also preserves overall performance across six
  representative text understanding and generation tasks. Further experiments indicate that NeuralDB
  maintains its effectiveness even when scaled to 100,000 facts (50x more than in prior work).
---
