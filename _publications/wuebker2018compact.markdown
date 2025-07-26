---
layout: publication
title: Compact Personalized Models For Neural Machine Translation
authors: Joern Wuebker, Patrick Simianer, John Denero
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: wuebker2018compact
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.01990'}]
tags: ["Fine-Tuning", "Model Architecture"]
short_authors: Joern Wuebker, Patrick Simianer, John Denero
---
We propose and compare methods for gradient-based domain adaptation of
self-attentive neural machine translation models. We demonstrate that a large
proportion of model parameters can be frozen during adaptation with minimal or
no reduction in translation quality by encouraging structured sparsity in the
set of offset tensors during learning via group lasso regularization. We
evaluate this technique for both batch and incremental adaptation across
multiple data sets and language pairs. Our system architecture - combining a
state-of-the-art self-attentive model with compact domain adaptation - provides
high quality personalized machine translation that is both space and time
efficient.