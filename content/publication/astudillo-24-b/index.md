---
title: 'Preferential Multi-Objective Bayesian Optimization'
date: '2024-08-01'
publishDate: '2024-08-21T22:34:17.512039Z'
authors:
- Raul Astudillo
- Kejun Li
- Maegan Tucker
- Chu Xin Cheng
- Aaron D Ames
- Yisong Yue
publication_types:
- '1'
abstract: Preferential Bayesian optimization (PBO) is a framework for optimizing a decision-maker's latent preferences over available design choices. While preferences often involve multiple conflicting objectives, existing work in PBO assumes that preferences can be encoded by a single objective function. For example, in robotic assistive devices, technicians often attempt to maximize user comfort while simultaneously minimizing mechanical energy consumption for longer battery life. Similarly, in autonomous driving policy design, decision-makers wish to understand the trade-offs between multiple safety and performance attributes before committing to a policy. To address this gap, we propose the first framework for PBO with multiple objectives. Within this framework, we present dueling scalarized Thompson sampling (DSTS), a multi-objective generalization of the popular dueling Thompson algorithm, which may be of interest beyond the PBO setting. We evaluate DSTS across four synthetic test functions and two simulated exoskeleton personalization and driving policy design tasks, showing that it outperforms several benchmarks. Finally, we prove that DSTS is asymptotically consistent. As a direct consequence, this result provides, to our knowledge, the first convergence guarantee for dueling Thompson sampling in the PBO setting.
featured: false
publication: '*Preprint*'
url_pdf: https://arxiv.org/pdf/2406.14699
---

