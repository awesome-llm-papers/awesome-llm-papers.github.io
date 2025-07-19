---
layout: publication
title: 'CGMH: Constrained Sentence Generation By Metropolis-hastings Sampling'
authors: Miao et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: miao2018cgmh
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.10996'}]
tags: [Reinforcement Learning, Training Techniques, Applications, AAAI]
---
In real-world applications of natural language generation, there are often
constraints on the target sentences in addition to fluency and naturalness
requirements. Existing language generation techniques are usually based on
recurrent neural networks (RNNs). However, it is non-trivial to impose
constraints on RNNs while maintaining generation quality, since RNNs generate
sentences sequentially (or with beam search) from the first word to the last.
In this paper, we propose CGMH, a novel approach using Metropolis-Hastings
sampling for constrained sentence generation. CGMH allows complicated
constraints such as the occurrence of multiple keywords in the target
sentences, which cannot be handled in traditional RNN-based approaches.
Moreover, CGMH works in the inference stage, and does not require parallel
corpora for training. We evaluate our method on a variety of tasks, including
keywords-to-sentence generation, unsupervised sentence paraphrasing, and
unsupervised sentence error correction. CGMH achieves high performance compared
with previous supervised methods for sentence generation. Our code is released
at https://github.com/NingMiao/CGMH