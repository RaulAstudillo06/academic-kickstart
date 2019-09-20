---
title: Multi-Attribute Bayesian Optimization under Utility Uncertainty (contributed poster)
event: NIPS workshop on Bayesian Optimization
event_url: https://bayesopt.github.io/

location: Long Beach Convention & Entertainment Center
address:
  street: 300 E Ocean Blvd
  city: Long Beach
  region: CA
  postcode: '94305'
  country: United States

summary: 
abstract: "We consider multi-attribute Bayesian optimization, where each design in an optimization
problem’s feasible space is associated with a vector of attributes that can
be evaluated via a time-consuming computer code, and each vector of attributes
is assigned a utility according to a decision-maker’s utility function. A standard
Bayesian optimization approach could be applied if the utility function were known
to us: we would place a Bayesian prior distribution over the composition of the
objective function, which returns a design’s vector of attributes, and the utility function,
which maps those attributes onto a utility. In contrast, we assume the utility
function cannot be evaluated and is known implicitly only to the decision-maker.
We propose a Bayesian optimization algorithm that chooses the designs to evaluate,
such that the expected utility of the design chosen by the decision-maker, according
to our algorithm’s estimate of the objective function, is large. In contrast with
existing approaches for multi-attribute optimization that focus on estimating a
Pareto frontier, our approach can take advantage of prior information about the
decision-maker’s utility, obtained from past experiences with the decision-maker
or from a utility elicitation process."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2017-12-09T9:00:00Z"
date_end: "2017-12-09T18:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["Raul Astudillo", "Peter I Frazier"]
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
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- internal-project

# Enable math on this page?
math: true
---
