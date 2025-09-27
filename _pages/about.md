---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am now a first-year Ph.D. student at the [College of AI](https://collegeai.tsinghua.edu.cn/), Tsinghua University, advised by Professor [Jingzhao Zhang](https://scholar.google.com/citations?user=8NudxYsAAAAJ&hl=en&oi=ao). I am also an intern of [Shanghai Qi Zhi Institute](https://www.sqz.ac.cn/). Previously, I did my undergraduate at School of Computer Science, Beijing Institute of Technology.

My research focuses on machine learning, both on the theoretical and empirical sides. On the theoretical side, I enjoy conducting various experiments and constructing appropriate and realistic theoretical frameworks based on the results. On the empirical side, I have hands-on experience with supervised fine-tuning of large-scale LLMs and reinforcement learning. Recently, I have been particularly interested in the optimization aspect of LLM pre-training and the RL aspect of post-training.

I have worked on topics including:
- Scalable Model Merging. 
- Optimization Algorithm for LLM.
- Training Dynamics of Neural Networks.
- Reasoning Large Language Model.
- Multi turn Agent.

<h2 class="section-title">Experiences</h2>
**Ant Group** (Apr. 2025 – Oct. 2025)  
*Research Intern at RL Lab*  

- Improved Reasoning LLM with RL, boosting a 1.5B model's AIME24 and AIME25 scores to 72.5 and 62.3, up over 10 points.

<h2 class="section-title">Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
