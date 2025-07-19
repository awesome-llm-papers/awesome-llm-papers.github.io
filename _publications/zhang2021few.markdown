---
layout: publication
title: Few-shot Intent Detection Via Contrastive Pre-training And Fine-tuning
authors: Zhang et al.
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: zhang2021few
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.06349'}]
tags: [Training Techniques, EMNLP, Few Shot, Fine Tuning, Datasets]
---
In this work, we focus on a more challenging few-shot intent detection
scenario where many intents are fine-grained and semantically similar. We
present a simple yet effective few-shot intent detection schema via contrastive
pre-training and fine-tuning. Specifically, we first conduct self-supervised
contrastive pre-training on collected intent datasets, which implicitly learns
to discriminate semantically similar utterances without using any labels. We
then perform few-shot intent detection together with supervised contrastive
learning, which explicitly pulls utterances from the same intent closer and
pushes utterances across different intents farther. Experimental results show
that our proposed method achieves state-of-the-art performance on three
challenging intent detection datasets under 5-shot and 10-shot settings.