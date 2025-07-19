---
layout: publication
title: 'Robbert-2022: Updating A Dutch Language Model To Account For Evolving Language
  Use'
authors: Delobelle Pieter, Winters Thomas, Berendt Bettina
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2022
bibkey: delobelle2022robbert
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.08192'}]
tags: [Model Architecture, Training Techniques, BERT, ACL, EMNLP, GPT, Transformer,
  Datasets]
---
Large transformer-based language models, e.g. BERT and GPT-3, outperform
previous architectures on most natural language processing tasks. Such language
models are first pre-trained on gigantic corpora of text and later used as
base-model for finetuning on a particular task. Since the pre-training step is
usually not repeated, base models are not up-to-date with the latest
information. In this paper, we update RobBERT, a RoBERTa-based state-of-the-art
Dutch language model, which was trained in 2019. First, the tokenizer of
RobBERT is updated to include new high-frequent tokens present in the latest
Dutch OSCAR corpus, e.g. corona-related words. Then we further pre-train the
RobBERT model using this dataset. To evaluate if our new model is a plug-in
replacement for RobBERT, we introduce two additional criteria based on concept
drift of existing tokens and alignment for novel tokens.We found that for
certain language tasks this update results in a significant performance
increase. These results highlight the benefit of continually updating a
language model to account for evolving language use.