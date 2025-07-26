---
layout: publication
title: Cross-domain Semantic Parsing Via Paraphrasing
authors: Yu Su, Xifeng Yan
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: su2017cross
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.05974'}]
tags: ["EMNLP"]
short_authors: Yu Su, Xifeng Yan
---
Existing studies on semantic parsing mainly focus on the in-domain setting.
We formulate cross-domain semantic parsing as a domain adaptation problem:
train a semantic parser on some source domains and then adapt it to the target
domain. Due to the diversity of logical forms in different domains, this
problem presents unique and intriguing challenges. By converting logical forms
into canonical utterances in natural language, we reduce semantic parsing to
paraphrasing, and develop an attentive sequence-to-sequence paraphrase model
that is general and flexible to adapt to different domains. We discover two
problems, small micro variance and large macro variance, of pre-trained word
embeddings that hinder their direct use in neural networks, and propose
standardization techniques as a remedy. On the popular Overnight dataset, which
contains eight domains, we show that both cross-domain training and
standardized pre-trained word embeddings can bring significant improvement.