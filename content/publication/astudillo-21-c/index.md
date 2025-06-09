---
title: 'Thinking inside the box: A tutorial on grey-box Bayesian optimization'
date: '2021-12-03'
publishDate: '2021-12-03T19:09:51.783898Z'
authors:
- Raul Astudillo
- Peter I. Frazier
publication_types:
- '1'
abstract: Bayesian optimization (BO) is a framework for global optimization of expensive-to-evaluate objective functions. Classical BO methods assume that the objective function is a black box. However, internal information about objective function computation is often available. For example, when optimizing a manufacturing line's throughput with simulation, we observe the number of parts waiting at each workstation, in addition to the overall throughput. Recent BO methods leverage such internal information to dramatically improve performance. We call these "grey-box" BO methods because they treat objective computation as partially observable and even modifiable, blending the black-box approach with so-called "white-box" first-principles knowledge of objective function computation. This tutorial describes these methods, focusing on BO of composite objective functions, where one can observe and selectively evaluate individual constituents that feed into the overall objective; and multi-fidelity BO, where one can evaluate cheaper approximations of the objective function by varying parameters of the evaluation oracle.
featured: false
publication: '*2021 Winter Simulation Conference (WSC)*'
url_pdf: https://people.orie.cornell.edu/pfrazier/pub/grey_box_tutorial.pdf
---

