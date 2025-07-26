---
layout: publication
title: Adversarial Learning With Contextual Embeddings For Zero-resource Cross-lingual
  Classification And NER
authors: Phillip Keung, Yichao Lu, Vikas Bhardwaj
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: keung2019adversarial
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00153'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Phillip Keung, Yichao Lu, Vikas Bhardwaj
---
Contextual word embeddings (e.g. GPT, BERT, ELMo, etc.) have demonstrated
state-of-the-art performance on various NLP tasks. Recent work with the
multilingual version of BERT has shown that the model performs very well in
zero-shot and zero-resource cross-lingual settings, where only labeled English
data is used to finetune the model. We improve upon multilingual BERT's
zero-resource cross-lingual performance via adversarial learning. We report the
magnitude of the improvement on the multilingual MLDoc text classification and
CoNLL 2002/2003 named entity recognition tasks. Furthermore, we show that
language-adversarial training encourages BERT to align the embeddings of
English documents and their translations, which may be the cause of the
observed performance gains.