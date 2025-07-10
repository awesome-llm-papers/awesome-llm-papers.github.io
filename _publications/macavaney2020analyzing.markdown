---
layout: publication
title: 'ABNIRML: Analyzing The Behavior Of Neural IR Models'
authors: Sean Macavaney, Sergey Feldman, Nazli Goharian, Doug Downey, Arman Cohan
conference: Transactions of the Association for Computational Linguistics
year: 2020
citations: 16
bibkey: macavaney2020analyzing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.00696'}]
tags: [Model Architecture, Ethics and Bias, RAG, Tools, Reinforcement Learning, BERT,
  Training Techniques]
---
Pretrained contextualized language models such as BERT and T5 have
established a new state-of-the-art for ad-hoc search. However, it is not yet
well-understood why these methods are so effective, what makes some variants
more effective than others, and what pitfalls they may have. We present a new
comprehensive framework for Analyzing the Behavior of Neural IR ModeLs
(ABNIRML), which includes new types of diagnostic probes that allow us to test
several characteristics -- such as writing styles, factuality, sensitivity to
paraphrasing and word order -- that are not addressed by previous techniques.
To demonstrate the value of the framework, we conduct an extensive empirical
study that yields insights into the factors that contribute to the neural
model's gains, and identify potential unintended biases the models exhibit.
Some of our results confirm conventional wisdom, like that recent neural
ranking models rely less on exact term overlap with the query, and instead
leverage richer linguistic information, evidenced by their higher sensitivity
to word and sentence order. Other results are more surprising, such as that
some models (e.g., T5 and ColBERT) are biased towards factually correct (rather
than simply relevant) texts. Further, some characteristics vary even for the
same base language model, and other characteristics can appear due to random
variations during model training.