---
layout: publication
title: Scaling Neural Machine Translation
authors: Ott et al.
conference: 'Proceedings of the Third Conference on Machine Translation: Research
  Papers'
year: 2018
bibkey: ott2018scaling
citations: 563
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.00187'}]
tags: [Training Techniques, Evaluation, WMT, Datasets, Reinforcement Learning]
---
Sequence to sequence learning models still require several days to reach
state of the art performance on large benchmark datasets using a single
machine. This paper shows that reduced precision and large batch training can
speedup training by nearly 5x on a single 8-GPU machine with careful tuning and
implementation. On WMT'14 English-German translation, we match the accuracy of
Vaswani et al. (2017) in under 5 hours when training on 8 GPUs and we obtain a
new state of the art of 29.3 BLEU after training for 85 minutes on 128 GPUs. We
further improve these results to 29.8 BLEU by training on the much larger
Paracrawl dataset. On the WMT'14 English-French task, we obtain a
state-of-the-art BLEU of 43.2 in 8.5 hours on 128 GPUs.