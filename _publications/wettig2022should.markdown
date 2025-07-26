---
layout: publication
title: Should You Mask 15% In Masked Language Modeling?
authors: Alexander Wettig, Tianyu Gao, Zexuan Zhong, Danqi Chen
conference: Proceedings of the 17th Conference of the European Chapter of the Association
  for Computational Linguistics
year: 2023
bibkey: wettig2022should
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.08005'}]
tags: ["EACL", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Wettig et al.
---
Masked language models (MLMs) conventionally mask 15% of tokens due to the
belief that more masking would leave insufficient context to learn good
representations; this masking rate has been widely used, regardless of model
sizes or masking strategies. In this work, we revisit this important choice of
MLM pre-training. We first establish that 15% is not universally optimal, and
larger models should adopt a higher masking rate. Specifically, we find that
masking 40% outperforms 15% for BERT-large size models on GLUE and SQuAD.
Interestingly, an extremely high masking rate of 80% can still preserve 95%
fine-tuning performance and most of the accuracy in linguistic probing,
challenging the conventional wisdom about the role of the masking rate. We then
examine the interplay between masking rates and masking strategies and find
that uniform masking requires a higher masking rate compared to sophisticated
masking strategies such as span or PMI masking. Finally, we argue that
increasing the masking rate has two distinct effects: it leads to more
corruption, which makes the prediction task more difficult; it also enables
more predictions, which benefits optimization. Using this framework, we revisit
BERT's 80-10-10 corruption strategy. Together, our results contribute to a
better understanding of MLM pre-training.