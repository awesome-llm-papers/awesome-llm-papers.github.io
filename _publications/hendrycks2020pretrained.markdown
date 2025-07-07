---
layout: publication
title: Pretrained Transformers Improve Out-of-distribution Robustness
authors: Dan Hendrycks et al.
conference: Arxiv
year: 2020
citations: 93
bibkey: hendrycks2020pretrained
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.06100'}]
tags: [Distillation, Transformer, Training Techniques, BERT, Efficiency and Optimization,
  Security, Model Architecture]
---
Although pretrained Transformers such as BERT achieve high accuracy on
in-distribution examples, do they generalize to new distributions? We
systematically measure out-of-distribution (OOD) generalization for seven NLP
datasets by constructing a new robustness benchmark with realistic distribution
shifts. We measure the generalization of previous models including bag-of-words
models, ConvNets, and LSTMs, and we show that pretrained Transformers'
performance declines are substantially smaller. Pretrained transformers are
also more effective at detecting anomalous or OOD examples, while many previous
models are frequently worse than chance. We examine which factors affect
robustness, finding that larger models are not necessarily more robust,
distillation can be harmful, and more diverse pretraining data can enhance
robustness. Finally, we show where future work can improve OOD robustness.