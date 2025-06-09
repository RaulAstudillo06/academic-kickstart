---
title: Multi-attribute Bayesian optimization under utility uncertainty
date: '2017-12-01'
publishDate: '2017-12-01T22:34:17.559820Z'
authors:
- <u>Raul Astudillo</u>
- Peter I. Frazier
publication_types:
- '1'
abstract: 'We consider multi-attribute Bayesian optimization, where each design in
  an optimization problem’s feasible space is associated with a vector of attributes
  that can be evaluated via a time-consuming computer code, and each vector of attributes
  is assigned a utility according to a decision-maker’s utility function. A standard
  Bayesian optimization approach could be applied if the utility function were known
  to us: we would place a Bayesian prior distribution over the composition of the
  objective function, which returns a design’s vector of attributes, and the utility
  function, which maps those attributes onto a utility. In contrast, we assume the
  utility function cannot be evaluated and is known implicitly only to the decision-maker.
  We propose a Bayesian optimization algorithm that chooses the designs to evaluate,
  such that the expected utility of the design chosen by the decision-maker, according
  to our algorithm’s estimate of the objective function, is large. In contrast with
  existing approaches for multi-attribute optimization that focus on estimating a
  Pareto frontier, our approach can take advantage of prior information about the
  decision-maker’s utility, obtained from past experiences with the decision-maker
  or from a utility elicitation process.'
featured: false
publication: '*NIPS Workshop on Bayesian Optimization*'
url_pdf: https://bayesopt.github.io/papers/2017/41.pdf
---

