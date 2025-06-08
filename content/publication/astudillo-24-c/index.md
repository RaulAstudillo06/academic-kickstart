---
title: 'Practical Bayesian Algorithm Execution via Posterior Sampling'
date: '2024-12-03'
publishDate: '2024-08-22T22:34:17.512039Z'
authors:
- Chu Xin Cheng
- Raul Astudillo
- Thomas Desautels
- Yisong Yue
publication_types:
- '1'
abstract: We consider Bayesian algorithm execution (BAX), a framework for efficiently selecting evaluation points of an expensive function to infer a property of interest encoded as the output of a base algorithm. Since the base algorithm typically requires more evaluations than are feasible, it cannot be directly applied. Instead, BAX methods sequentially select evaluation points using a probabilistic numerical approach. Current BAX methods use expected information gain to guide this selection. However, this approach is computationally intensive. Observing that, in many tasks, the property of interest corresponds to a target set of points defined by the function, we introduce PS-BAX, a simple, effective, and scalable BAX method based on posterior sampling. PS-BAX is applicable to a wide range of problems, including many optimization variants and level set estimation. Experiments across diverse tasks demonstrate that PS-BAX performs competitively with existing baselines while being significantly faster, simpler to implement, and easily parallelizable, setting a strong baseline for future research. Additionally, we establish conditions under which PS-BAX is asymptotically convergent, offering new insights into posterior sampling as an algorithm design paradigm.
featured: false
publication: '*Advances in Neural Information Processing Systems*'
url_pdf: https://arxiv.org/pdf/2410.20596
---

