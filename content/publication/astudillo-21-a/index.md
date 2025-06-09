---
title: Bayesian optimization of function networks
date: '2021-12-01'
publishDate: '2021-12-01T22:34:17.453262Z'
authors:
- Raul Astudillo
- Peter I. Frazier
publication_types:
- '1'
abstract: 'We consider Bayesian optimization of the output of a network of functions,
  where each function takes as input the output of its parent nodes, and where the
  network takes significant time to evaluate. Such problems arise, for example, in
  reinforcement learning, engineering design, and manufacturing.  While the standard
  Bayesian optimization approach observes only the final output, our approach delivers
  greater query efficiency by leveraging information that the former ignores: intermediate
  output within the network. This is achieved by modeling the nodes of the network
  using Gaussian processes and choosing the points to evaluate using, as our acquisition
  function, the expected improvement computed with respect to the implied posterior
  on the objective function. Although the non-Gaussian nature of this posterior prevents
  computing our acquisition function in closed form, we maximize it using a sample
  average approximation approach. In addition, we show that our method is asymptotically
  consistent, meaning that it finds a globally optimal solution as the number of evaluations
  grows to infinity, thus generalizing previously known convergence results for the
  expected improvement acquisition function.  This holds even though it might not
  measure densely, instead leveraging problem structure to leave regions unexplored.
  Finally, our approach dramatically outperforms standard BO methods in several synthetic
  and real-world problems.'
featured: false
publication: '*Advances in Neural Information Processing Systems*'
url_pdf: https://arxiv.org/pdf/2112.15311
---
