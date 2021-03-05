---
title: Bayesian Optimization of Function Networks
event: SIAM Conference on Computational Science and Engineering 2021
event_url: https://www.siam.org/conferences/cm/conference/cse21

location: Virtual

summary: 
abstract: "We consider Bayesian optimization of objective functions whose evaluations require evaluating a series of expensive-to-evaluate functions arranged in a network so that each function takes as input the output of its parent nodes. While the standard Bayesian optimization approach observes only the objective value, our approach delivers greater sample efficiency by observing information that the standard approach ignores: intermediate output within the network. Our approach models the nodes of the network using independent Gaussian processes and chooses the points to evaluate using as its acquisition function the expected improvement computed with respect to the implied posterior on the objective function. Although this acquisition function cannot be computed in closed form, we maximize it using a sample average approximation approach. Numerical experiments show that our approach substantially outperforms standard Bayesian optimization benchmarks"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-03-04T09:45:00Z"
date_end: "2021-03-04T10:00:00Z"
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
