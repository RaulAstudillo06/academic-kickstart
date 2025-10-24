---
title: 'Steering generative models with experimental data for protein fitness optimization'
date: '2025-05-21'
publishDate: '2025-05-21T22:34:17.512039Z'
authors:
- Jason Yang
- Wenda Chu
- Daniel Khalil
- <u>Raul Astudillo</u>
- Bruce J. Wittmann
- Frances H. Arnold
- Yisong Yue
publication_types:
- '1'
abstract: Protein fitness optimization involves finding a protein sequence that maximizes desired quantitative properties in a combinatorially large design space of possible sequences. Recent developments in steering protein generative models (e.g diffusion models, language models) offer a promising approach. However, by and large, past studies have optimized surrogate rewards and/or utilized large amounts of labeled data for steering, making it unclear how well existing methods perform and compare to each other in real-world optimization campaigns where fitness is measured by low-throughput wet-lab assays. In this study, we explore fitness optimization using small amounts (hundreds) of labeled sequence-fitness pairs and comprehensively evaluate strategies such as classifier guidance and posterior sampling for guiding generation from different discrete diffusion models of protein sequences. We also demonstrate how guidance can be integrated into adaptive sequence selection akin to Thompson sampling in Bayesian optimization, showing that plug-and-play guidance strategies offer advantages compared to alternatives such as reinforcement learning with protein language models.
featured: false
publication: '*Advances in Neural Information Processing Systems*'
url_pdf: https://arxiv.org/pdf/2505.15093
---

