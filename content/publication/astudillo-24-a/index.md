---
title: 'Bayesian Optimization of Function Networks with Partial Evaluations'
date: '2024-07-01'
publishDate: '2024-07-21T22:34:17.512039Z'
authors:
- Poompol Buathong
- Jiayue Wan
- Raul Astudillo
- Sam Daulton
- Max Balandat
- Peter Frazier
publication_types:
- '1'
abstract: Bayesian optimization is a powerful framework for optimizing functions that are expensive or time-consuming to evaluate. Recent work has considered Bayesian optimization of function networks (BOFN), where the objective function is given by a network of functions, each taking as input the output of previous nodes in the network as well as additional parameters. Leveraging this network structure has been shown to yield significant performance improvements. Existing BOFN algorithms for general-purpose networks evaluate the full network at each iteration. However, many real-world applications allow for evaluating nodes individually. To exploit this, we propose a novel knowledge gradient acquisition function that chooses which node and corresponding inputs to evaluate in a cost-aware manner, thereby reducing query costs by evaluating only on a part of the network at each step. We provide an efficient approach to optimizing our acquisition function and show that it outperforms existing BOFN methods and other benchmarks across several synthetic and real-world problems. Our acquisition function is the first to enable cost-aware optimization of a broad class of function networks.
featured: false
publication: '*Proceedings of the 41st International Conference on Machine Learning*'
url_pdf: https://arxiv.org/pdf/2311.02146
---

