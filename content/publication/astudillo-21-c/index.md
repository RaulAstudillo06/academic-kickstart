---
title: 'Thinking Inside the Box: A Tutorial on Grey-Box Bayesian Optimization'
date: '2021-12-01'
authors:
- Raul Astudillo
- Peter I Frazier
publication_types:
- '1'
abstract: Bayesian optimization (BO) is a sample-efficient approach to optimizing
  costly-to-evaluate black-box functions. Most BO methods ignore how evaluation costs
  may vary over the optimization domain. However, these costs can be highly heterogeneous
  and are often unknown in advance in many practical settings, such as hyperparameter
  tuning of machine learning algorithms, or physics-based simulation optimization.
  Moreover, those few existing methods that acknowledge cost heterogeneity do not
  naturally accommodate a budget constraint on the total evaluation cost. This combination
  of unknown costs and a budget constraint introduces a new dimension to the exploration-exploitation
  trade-off, where learning about the cost incurs a cost itself. Existing approaches
  do not reason about the various trade-offs of this problem in a principled way,
  leading often to poor performance. We formalize this claim by proving that the expected
  improvement and the expected improvement per unit of cost, arguably the two most
  widely used acquisition functions in practice, can be arbitrarily inferior with
  respect to the optimal non-myopic policy. To overcome the shortcomings of existing
  approaches,  we propose the budgeted multi-step expected improvement, a non-myopic
  acquisition function that  generalizes classical expected improvement to the setting
  of heterogeneous and unknown evaluation costs. We show that our acquisition function
  outperforms existing BO methods in a variety of synthetic and realistic problems.
featured: false
publication: '*Proceedings of the 2021 Winter Simulation Conference*'
publishDate: '2021-10-30T19:03:20.506155Z'
---

