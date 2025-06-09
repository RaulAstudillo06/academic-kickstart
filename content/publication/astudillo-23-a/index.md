---
title: 'qEUBO: A decision-theoretic acquisition function for preferential Bayesian optimization'
date: '2023-04-01'
publishDate: '2023-04-01T22:34:17.512039Z'
authors:
-  <u>Raul Astudillo</u>
- Zhiyuan Jerry Lin
- Eytan Bakshy
- Peter I. Frazier
publication_types:
- '1'
abstract: Preferential Bayesian optimization (PBO) is a framework for optimizing a decision maker’s latent utility function using preference feedback. This work introduces the expected utility of the best option (qEUBO) as a novel acquisition function for PBO. When the decision maker’s responses are noise-free, we show that qEUBO is one-step Bayes optimal and thus equivalent to the popular knowledge gradient acquisition function. We also show that qEUBO enjoys an additive constant approximation guarantee to the one-step Bayes-optimal policy when the decision maker’s responses are corrupted by noise. We provide an extensive evaluation of qEUBO and demonstrate that it outperforms the state-of-the-art acquisition functions for PBO across many settings. Finally, we show that, under sufficient regularity conditions, qEUBO’s Bayesian simple regret converges to zero at a rate o(1/n) as the number of queries, n, goes to infinity. In contrast, we show that simple regret under qEI, a popular acquisition function for standard BO often used for PBO, can fail to converge to zero. Enjoying superior performance, simple computation, and a grounded decision-theoretic justification, qEUBO is a promising acquisition function for PBO.
featured: false
publication: '*Proceedings of the 26th International Conference on Artificial Intelligence
  and Statistics*'
url_pdf: https://arxiv.org/pdf/2303.15746.pdf
---

