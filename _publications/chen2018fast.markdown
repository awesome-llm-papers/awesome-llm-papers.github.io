---
layout: publication
title: Fast Abstractive Summarization With Reinforce-selected Sentence Rewriting
authors: Yen-chun Chen, Mohit Bansal
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: chen2018fast
citations: 623
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.11080'}]
tags: ["Reinforcement Learning"]
short_authors: Yen-chun Chen, Mohit Bansal
---
Inspired by how humans summarize long documents, we propose an accurate and
fast summarization model that first selects salient sentences and then rewrites
them abstractively (i.e., compresses and paraphrases) to generate a concise
overall summary. We use a novel sentence-level policy gradient method to bridge
the non-differentiable computation between these two neural networks in a
hierarchical way, while maintaining language fluency. Empirically, we achieve
the new state-of-the-art on all metrics (including human evaluation) on the
CNN/Daily Mail dataset, as well as significantly higher abstractiveness scores.
Moreover, by first operating at the sentence-level and then the word-level, we
enable parallel decoding of our neural generative model that results in
substantially faster (10-20x) inference speed as well as 4x faster training
convergence than previous long-paragraph encoder-decoder models. We also
demonstrate the generalization of our model on the test-only DUC-2002 dataset,
where we achieve higher scores than a state-of-the-art model.