---
layout: publication
title: Non-autoregressive Machine Translation With Latent Alignments
authors: Chitwan Saharia, William Chan, Saurabh Saxena, Mohammad Norouzi
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: saharia2020non
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.07437'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Saharia et al.
---
This paper presents two strong methods, CTC and Imputer, for
non-autoregressive machine translation that model latent alignments with
dynamic programming. We revisit CTC for machine translation and demonstrate
that a simple CTC model can achieve state-of-the-art for single-step
non-autoregressive machine translation, contrary to what prior work indicates.
In addition, we adapt the Imputer model for non-autoregressive machine
translation and demonstrate that Imputer with just 4 generation steps can match
the performance of an autoregressive Transformer baseline. Our latent alignment
models are simpler than many existing non-autoregressive translation baselines;
for example, we do not require target length prediction or re-scoring with an
autoregressive model. On the competitive WMT'14 En\\(\rightarrow\\)De task, our CTC
model achieves 25.7 BLEU with a single generation step, while Imputer achieves
27.5 BLEU with 2 generation steps, and 28.0 BLEU with 4 generation steps. This
compares favourably to the autoregressive Transformer baseline at 27.8 BLEU.