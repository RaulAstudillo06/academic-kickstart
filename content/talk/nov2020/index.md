---
title: Bayesian Optimization of Function Networks
event: INFORMS Annual Meeting 2020
event_url: http://meetings2.informs.org/wordpress/annual2020/

location: Virtual

summary: 
abstract: "We consider Bayesian optimization (BO) of objective functions whose evaluations require evaluating a series of expensive-to-evaluate functions arranged in a network so that each function takes as input the output of its parent nodes. While these problems can be approached using standard techniques, we propose a novel approach that leverages their structure to improve sampling efficiency. Our approach models the individual nodes of the network using independent Gaussian processes and chooses where to sample using as acquisition function the expected improvement evaluated on the implied posterior on the objective function. Although this acquisition function cannot be computed in closed form, we provide an efficient sample average approximation approach to maximize it. Numerical experiments show that our approach dramatically outperforms standard BO benchmarks."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-11-10T12:30:00Z"
date_end: "2020-11-10T12:45:00Z"
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
