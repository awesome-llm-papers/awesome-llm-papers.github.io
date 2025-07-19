---
layout: publication
title: Learning To Extract Coherent Summary Via Deep Reinforcement Learning
authors: Wu Yuxiang, Hu Baotian
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: wu2018learning
citations: 133
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.07036'}]
tags: [Agentic, Evaluation, Reinforcement Learning, AAAI, Datasets]
---
Coherence plays a critical role in producing a high-quality summary from a
document. In recent years, neural extractive summarization is becoming
increasingly attractive. However, most of them ignore the coherence of
summaries when extracting sentences. As an effort towards extracting coherent
summaries, we propose a neural coherence model to capture the cross-sentence
semantic and syntactic coherence patterns. The proposed neural coherence model
obviates the need for feature engineering and can be trained in an end-to-end
fashion using unlabeled data. Empirical results show that the proposed neural
coherence model can efficiently capture the cross-sentence coherence patterns.
Using the combined output of the neural coherence model and ROUGE package as
the reward, we design a reinforcement learning method to train a proposed
neural extractive summarizer which is named Reinforced Neural Extractive
Summarization (RNES) model. The RNES model learns to optimize coherence and
informative importance of the summary simultaneously. Experimental results show
that the proposed RNES outperforms existing baselines and achieves
state-of-the-art performance in term of ROUGE on CNN/Daily Mail dataset. The
qualitative evaluation indicates that summaries produced by RNES are more
coherent and readable.