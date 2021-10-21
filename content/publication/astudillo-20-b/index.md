---
title: Bayesian Optimization of Risk Measures
date: '2020-01-01'
publishDate: '2021-10-21T22:22:08.022239Z'
authors:
- Sait Cakmak
- Raul Astudillo
- Peter I Frazier
- Enlu Zhou
publication_types:
- '1'
abstract: We consider Bayesian optimization of objective functions of the form $h̊o[
  F(x, W) ]$, where $F$ is a black-box expensive-to-evaluate function and $o̊$ denotes
  either the VaR or CVaR risk measure, computed with respect to the randomness induced
  by the environmental random variable $W$. Such problems arise in decision making
  under uncertainty, such as in portfolio optimization and robust systems design.
  We propose a family of novel Bayesian optimization algorithms that exploit the structure
  of the objective function to substantially improve sampling efficiency. Instead
  of modeling the objective function directly as is typical in Bayesian optimization,
  these algorithms model $F$ as a Gaussian process, and use the implied posterior
  on the objective function to decide which points to evaluate. We demonstrate the
  effectiveness of our approach in a variety of numerical experiments.
featured: false
publication: '*Advances in Neural Information Processing Systems*'
url_pdf: https://proceedings.neurips.cc/paper/2020/file/e8f2779682fd11fa2067beffc27a9192-Paper.pdf
---

