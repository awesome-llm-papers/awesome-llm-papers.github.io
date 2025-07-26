---
layout: publication
title: 'Multifit: Efficient Multi-lingual Language Model Fine-tuning'
authors: Julian Martin Eisenschlos, Sebastian Ruder, Piotr Czapla, Marcin Kardas,
  Sylvain Gugger, Jeremy Howard
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: eisenschlos2019multifit
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.04761'}]
tags: ["Datasets", "EMNLP", "Fine-Tuning", "Training Techniques"]
short_authors: Eisenschlos et al.
---
Pretrained language models are promising particularly for low-resource
languages as they only require unlabelled data. However, training existing
models requires huge amounts of compute, while pretrained cross-lingual models
often underperform on low-resource languages. We propose Multi-lingual language
model Fine-Tuning (MultiFiT) to enable practitioners to train and fine-tune
language models efficiently in their own language. In addition, we propose a
zero-shot method using an existing pretrained cross-lingual model. We evaluate
our methods on two widely used cross-lingual classification datasets where they
outperform models pretrained on orders of magnitude more data and compute. We
release all models and code.