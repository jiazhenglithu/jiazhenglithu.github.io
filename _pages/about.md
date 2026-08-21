---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am now a second-year Ph.D. student at the [College of AI](https://collegeai.tsinghua.edu.cn/), Tsinghua University, advised by Professor [Jingzhao Zhang](https://scholar.google.com/citations?user=8NudxYsAAAAJ&hl=en&oi=ao).

I am a deeply interest-driven individual, and I pursue research purely out of passion. I firmly believe that exceptional ideas and groundbreaking advancements in academia often emerge from open exchanges and the collision of diverse perspectives. If you have any insights, differing opinions on my work, or fresh ideas you wish to share, I would be truly grateful to hear from you.

My preferred email: <Foreverlasting1202@outlook.com>.

I welcome any opportunity to connect and exchange ideas with you!

<div class="page-nav">
  <a href="#research-interest">Research Interest</a>
  <a href="#experiences">Experiences</a>
  <a href="#publications">Publications</a>
  <a href="#projects">Projects</a>
</div>

<h2 id="research-interest" class="section-title">Research Interest</h2>
My research focuses on machine learning, both on the theoretical and empirical sides. On the theoretical side, I enjoy conducting various experiments and constructing appropriate and realistic theoretical frameworks based on the results. On the empirical side, I have hands-on experience with supervised fine-tuning of large-scale LLMs and reinforcement learning. Recently, I have been particularly interested in the optimization aspect of LLM pre-training and the RL aspect of post-training.

I have worked on topics including:
- Scalable Model Merging. 
- Optimization Algorithm for LLM.
- Training Dynamics of Neural Networks.
- Reasoning Large Language Model.
- Multi turn Agent.


<h2 id="experiences" class="section-title">Experiences</h2>
**ByteDance Seed** (Nov. 2025 – Present)  
*Research Intern, LLM Pre-training*  

- Research on efficient pretraining for large language models.
- Accelerating Optimization for LLMs.

**Ant Group RL Lab** (Apr. 2025 – Oct. 2025)  
*Research Intern, LLM Post-training*  

- Improved Reasoning LLM with RL, boosting a 1.5B model's AIME24 and AIME25 scores to 72.5 and 62.3, up over 10 points.
- Attempted to enhance Reasoning LLM using the approach of multi-turn agent.


<h2 id="publications" class="section-title">Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2 id="projects" class="section-title">Projects</h2>

**LucidGPT** &nbsp; [<i class="fab fa-github"></i>](https://github.com/foreverlasting1202/LucidGPT)  
Clean GPT-style pretraining with:
- Simple launch commands.
- Multi optimizer modes.
- Built-in benchmark evaluation during/after training.
- Optimizer and activation monitors for debugging training stability.

**What-s-up Chat Software** &nbsp; [<i class="fab fa-github"></i>](https://github.com/foreverlasting1202/What-s-up)  
- Developed a full-featured chat software.
- Backend communication, functional testing, and debugging.
