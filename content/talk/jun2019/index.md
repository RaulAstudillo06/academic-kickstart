---
title: Bayesian Optimization of Composite Functions
event: International Conference on Machine Learning 2019
event_url: https://icml.cc/Conferences/2019

location: Room 101, Long Beach Convention & Entertainment Center
address:
  street: 300 E Ocean Blvd
  city: Long Beach
  region: CA
  postcode: '94305'
  country: United States

summary: 
abstract: "We consider optimization of composite objective functions, i.e., of the form f(x)=g(h(x)), where h is a black-box derivative-free expensive-to-evaluate function with vector-valued outputs, and g is a cheap-to-evaluate function taking vector-valued inputs. While these problems can be solved with standard Bayesian optimization, we propose a novel approach that exploits the composite structure of the objective function to substantially improve sampling efficiency. Our approach models h using a multi-output Gaussian process and chooses where to sample using a natural generalization of the expected improvement acquisition function, called Expected Improvement for Composite Functions (EI-CF). Although EI-CF cannot be computed in closed form, we provide a novel stochastic gradient estimator that allows its efficient maximization. We then show that our approach is asymptotically consistent, i.e., that it recovers a globally optimal solution as sampling effort grows to infinity, generalizing previous convergence results for classical EI. Numerical experiments show our approach dramatically outperforms standard Bayesian optimization benchmarks, achieving simple regret that is smaller by several orders of magnitude."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-06-12T17:05:00Z"
date_end: "2019-12-07T17:10:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["Raul Astudillo", "Peter I Frazier"]
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption:

links:
url_code: https://github.com/RaulAstudillo06/BOCF
url_pdf: "http://proceedings.mlr.press/v97/astudillo19a/astudillo19a.pdf"
url_slides: https://icml.cc/media/Slides/icml/2019/101(12-16-00)-12-17-05-5108-bayesian_optimi.pdf
url_video: https://slideslive.com/38917278/probabilistic-inference

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:

# Enable math on this page?
math: true
---
