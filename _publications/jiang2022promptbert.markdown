---
layout: publication
title: 'Promptbert: Improving BERT Sentence Embeddings With Prompts'
authors: Jiang et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: jiang2022promptbert
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.04337'}]
tags: [Training Techniques, EMNLP, Prompting, Ethics And Bias, BERT, Model Architecture]
---
We propose PromptBERT, a novel contrastive learning method for learning
better sentence representation. We firstly analyze the drawback of current
sentence embedding from original BERT and find that it is mainly due to the
static token embedding bias and ineffective BERT layers. Then we propose the
first prompt-based sentence embeddings method and discuss two prompt
representing methods and three prompt searching methods to make BERT achieve
better sentence embeddings. Moreover, we propose a novel unsupervised training
objective by the technology of template denoising, which substantially shortens
the performance gap between the supervised and unsupervised settings. Extensive
experiments show the effectiveness of our method. Compared to SimCSE,
PromptBert achieves 2.29 and 2.58 points of improvement based on BERT and
RoBERTa in the unsupervised setting.