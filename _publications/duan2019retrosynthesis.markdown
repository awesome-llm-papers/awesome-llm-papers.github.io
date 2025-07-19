---
layout: publication
title: Retrosynthesis With Attention-based NMT Model And Chemical Analysis Of The
  "wrong" Predictions
authors: Duan et al.
conference: RSC Advances
year: 2019
bibkey: duan2019retrosynthesis
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.00727'}]
tags: [Model Architecture, Training Techniques, Attention Mechanism]
---
We cast retrosynthesis as a machine translation problem by introducing a
special Tensor2Tensor, an entire attention-based and fully data-driven model.
Given a data set comprising about 50,000 diverse reactions extracted from USPTO
patents, the model significantly outperforms seq2seq model (34.7%) on a top-1
accuracy by achieving 54.1%. For yielding better results, parameters such as
batch size and training time are thoroughly investigated to train the model.
Additionally, we offer a novel insight into the causes of grammatically invalid
SMILES, and conduct a test in which experienced chemists pick out and analyze
the "wrong" predictions that may be chemically plausible but differ from the
ground truth. Actually, the effectiveness of our model is un-derestimated and
the "true" top-1 accuracy can reach to 64.6%.