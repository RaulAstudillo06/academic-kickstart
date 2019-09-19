---
title: "Bayesian Optimization of Composite Functions"
date: 2019-06-01
publishDate: 2019-09-19T02:41:18.641233Z
authors: ["Raul Astudillo", "Peter I Frazier"]
publication_types: ["1"]
abstract: "We consider optimization of composite objective functions, i.e., of the form $f(x)=g(h(x))$, where $h$ is a black-box derivative-free expensive-to-evaluate function with vector-valued outputs, and $g$ is a cheap-to-evaluate real-valued function. While these problems can be solved with standard Bayesian optimization, we propose a novel approach that exploits the composite structure of the objective function to substantially improve sampling efficiency. Our approach models $h$ using a multi-output Gaussian process and chooses where to sample using the expected improvement evaluated on the implied non-Gaussian posterior on $f$, which we call expected improvement for composite functions (EI-CF). Although EI-CF cannot be computed in closed form, we provide a novel stochastic gradient estimator that allows its efficient maximization. We also show that our approach is asymptotically consistent, i.e., that it recovers a globally optimal solution as sampling effort grows to infinity, generalizing previous convergence results for classical expected improvement. Numerical experiments show that our approach dramatically outperforms standard Bayesian optimization benchmarks, reducing simple regret by several orders of magnitude."
featured: false
publication: "*Proceedings of the 36th International Conference on Machine Learning*"
url_pdf: "http://proceedings.mlr.press/v97/astudillo19a/astudillo19a.pdf"
---

