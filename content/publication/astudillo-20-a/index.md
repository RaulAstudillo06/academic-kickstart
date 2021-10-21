---
title: Multi-Attribute Bayesian Optimization With Interactive Preference Learning
date: '2020-07-01'
publishDate: '2021-10-21T22:34:17.512039Z'
authors:
- Raul Astudillo
- Peter I Frazier
publication_types:
- '1'
abstract: We consider black-box global optimization of time-consuming-to-evaluate
  functions on behalf of a decision-maker (DM) whose preferences must be learned.
  Each feasible design is associated with a time-consuming-to-evaluate vector of attributes
  and each vector of attributes is assigned a utility by the DM's utility function,
  which may be learned approximately using preferences expressed over pairs of attribute
  vectors. Past work has used a point estimate of this utility function as if it were
  error-free within single-objective optimization. However, utility estimation errors
  may yield a poor suggested design. Furthermore, this approach produces a single
  suggested \"best\" design, whereas DMs often prefer to choose from a menu. We propose
  a novel multi-attribute Bayesian optimization with preference learning approach.
  Our approach acknowledges the uncertainty in preference estimation and implicitly
  chooses designs to evaluate that are good not just for a single estimated utility
  function but a range of likely ones. The outcome of our approach is a menu of designs
  and evaluated attributes from which the DM makes a final selection. We demonstrate
  the value and flexibility of our approach in a variety of experiments.
featured: false
publication: '*Proceedings of the 23rd International Conference on Artificial Intelligence
  and Statistics*'
url_pdf: https://arxiv.org/pdf/1911.05934.pdf
---

