---
layout: publication
title: A Unified Model For Extractive And Abstractive Summarization Using Inconsistency
  Loss
authors: Wan-ting Hsu, Chieh-kai Lin, Ming-ying Lee, Kerui Min, Jing Tang, Min Sun
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: hsu2018unified
citations: 279
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.06266'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Hsu et al.
---
We propose a unified model combining the strength of extractive and
abstractive summarization. On the one hand, a simple extractive model can
obtain sentence-level attention with high ROUGE scores but less readable. On
the other hand, a more complicated abstractive model can obtain word-level
dynamic attention to generate a more readable paragraph. In our model,
sentence-level attention is used to modulate the word-level attention such that
words in less attended sentences are less likely to be generated. Moreover, a
novel inconsistency loss function is introduced to penalize the inconsistency
between two levels of attentions. By end-to-end training our model with the
inconsistency loss and original losses of extractive and abstractive models, we
achieve state-of-the-art ROUGE scores while being the most informative and
readable summarization on the CNN/Daily Mail dataset in a solid human
evaluation.