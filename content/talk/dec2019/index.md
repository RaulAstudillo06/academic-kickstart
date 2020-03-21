---
title: Bayesian Optimization of Composite Functions
event: Winter Simulation Conference 2019
event_url: https://meetings2.informs.org/wordpress/wsc2019/

location: Gaylord National Resort & Conference Center
address:
  street:
  city: Fort Washington
  region: MD
  postcode: '20745'
  country: United States

summary: 
abstract: "We consider optimization of composite objective functions, i.e., of the form $f(x)=g(h(x))$, where $h$ is a black-box derivative-free expensive-to-evaluate function with vector-valued outputs, and $g$ is a cheap-to-evaluate real-valued
function. While these problems can be solved with standard Bayesian optimization, we propose a novel approach that exploits the composite structure of the objective function to substantially improve sampling efficiency. Our approach models $h$ using a multi-output Gaussian process and chooses where to sample using the expected improvement evaluated on the implied non-Gaussian posterior on $f$, which we call expected improvement for composite functions (EI-CF). Although EI-CF cannot be computed in closed form, we provide a novel stochastic gradient estimator that allows its efficient maximization. We also show that our approach is asymptotically consistent, generalizing previous convergence results for classical expected improvement. Numerical experiments show that our approach dramatically outperforms standard Bayesian optimization benchmarks"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-12-08T15:30:00Z"
date_end: "2019-12-08T17:20:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["Raul Astudillo"]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption:

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

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
