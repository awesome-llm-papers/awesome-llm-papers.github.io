---
layout: publication
title: Latent-variable Non-autoregressive Neural Machine Translation With Deterministic
  Inference Using A Delta Posterior
authors: Raphael Shu, Jason Lee, Hideki Nakayama, Kyunghyun Cho
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: shu2019latent
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.07181'}]
tags: ["AAAI"]
short_authors: Shu et al.
---
Although neural machine translation models reached high translation quality,
the autoregressive nature makes inference difficult to parallelize and leads to
high translation latency. Inspired by recent refinement-based approaches, we
propose LaNMT, a latent-variable non-autoregressive model with continuous
latent variables and deterministic inference procedure. In contrast to existing
approaches, we use a deterministic inference algorithm to find the target
sequence that maximizes the lowerbound to the log-probability. During
inference, the length of translation automatically adapts itself. Our
experiments show that the lowerbound can be greatly increased by running the
inference algorithm, resulting in significantly improved translation quality.
Our proposed model closes the performance gap between non-autoregressive and
autoregressive approaches on ASPEC Ja-En dataset with 8.6x faster decoding. On
WMT'14 En-De dataset, our model narrows the gap with autoregressive baseline to
2.0 BLEU points with 12.5x speedup. By decoding multiple initial latent
variables in parallel and rescore using a teacher model, the proposed model
further brings the gap down to 1.0 BLEU point on WMT'14 En-De task with 6.8x
speedup.