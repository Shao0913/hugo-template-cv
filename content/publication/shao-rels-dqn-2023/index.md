---
title: 'RELS-DQN: A Robust and Efficient Local Search Framework for Combinatorial
  Optimization'
authors:
- Yuanhang Shao
- Tonmoy Dey
- Nikola Vuckovic
- Luke Van Popering
- Alan Kuhnle
date: '2023-04-01'
publishDate: '2024-04-15T15:43:18.287503Z'
publication_types: ["article"]
publication: '*arXiv*'
abstract: Combinatorial optimization (CO) aims to efficiently find the best solution
  to NP-hard problems ranging from statistical physics to social media marketing.
  A wide range of CO applications can benefit from local search methods because they
  allow reversible action over greedy policies. Deep Q-learning (DQN) using message-passing
  neural networks (MPNN) has shown promise in replicating the local search behavior
  and obtaining comparable results to the local search algorithms. However, the over-smoothing
  and the information loss during the iterations of message passing limit its robustness
  across applications, and the large message vectors result in memory inefficiency.
  Our paper introduces RELS-DQN, a lightweight DQN framework that exhibits the local
  search behavior while providing practical scalability. Using the RELS-DQN model
  trained on one application, it can generalize to various applications by providing
  solution values higher than or equal to both the local search algorithms and the
  existing DQN models while remaining efficient in runtime and memory.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2304.06048
  url_code: 'https://gitlab.com/Shao1206/rels-dqn'
---
