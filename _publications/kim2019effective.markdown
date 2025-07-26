---
layout: publication
title: Effective Cross-lingual Transfer Of Neural Machine Translation Models Without
  Shared Vocabularies
authors: Yunsu Kim, Yingbo Gao, Hermann Ney
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: kim2019effective
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.05475'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Yunsu Kim, Yingbo Gao, Hermann Ney
---
Transfer learning or multilingual model is essential for low-resource neural
machine translation (NMT), but the applicability is limited to cognate
languages by sharing their vocabularies. This paper shows effective techniques
to transfer a pre-trained NMT model to a new, unrelated language without shared
vocabularies. We relieve the vocabulary mismatch by using cross-lingual word
embedding, train a more language-agnostic encoder by injecting artificial
noises, and generate synthetic data easily from the pre-training data without
back-translation. Our methods do not require restructuring the vocabulary or
retraining the model. We improve plain NMT transfer by up to +5.1% BLEU in five
low-resource translation tasks, outperforming multilingual joint training by a
large margin. We also provide extensive ablation studies on pre-trained
embedding, synthetic data, vocabulary size, and parameter freezing for a better
understanding of NMT transfer.