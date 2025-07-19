---
layout: publication
title: Inroads To A Structured Data Natural Language Bijection And The Role Of LLM
  Annotation
authors: Vente Blake
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2024
bibkey: vente2024inroads
citations: 152
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.07190'}]
tags: [Model Architecture, Training Techniques, Efficiency And Optimization, Evaluation,
  ACL, Transformer, Reinforcement Learning]
---
This work finds limited evidence supporting the theory that using multiple
tasks with sequence-to-sequence transformer language models can improve
performance on some metrics. In particular, the multi-task generalist t5-small
outperforms the specialist t5-small with a \\(F_1\\) of \\(0.771\\) up from \\(0.692\\),
which may point to underlying cross-task knowledge generalization. This further
suggests that even with the same network, "re-using" the same data in a
different way may lead to higher performance in some metrics. However, the
inverse task alone is likely only an optimization strategy, since it does not
yield a significant general improvement at the model sizes explored in this
work. Also, adding \\(\approx 4500\\) LLM annotated records (interlaced with the
\\(12800\\) WebNLG training records) does not substantially change automatic metric
performance compared to the same t5-small model without the synthetic data.
This may be due to a learning capacity bottleneck on account of model size, and
decreases observed may be due to distributional differences in the corpora.
Future research using larger models or human evaluation is required to more
fully explain the mechanisms contributing to performance on these tasks.