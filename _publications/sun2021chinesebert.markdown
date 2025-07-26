---
layout: publication
title: 'Chinesebert: Chinese Pretraining Enhanced By Glyph And Pinyin Information'
authors: Zijun Sun, Xiaoya Li, Xiaofei Sun, Yuxian Meng, Xiang Ao, Qing He, Fei Wu,
  Jiwei Li
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: sun2021chinesebert
citations: 150
additional_links: [{name: Code, url: 'https://github.com/ShannonAI/ChineseBert'},
  {name: Paper, url: 'https://arxiv.org/abs/2106.16038'}]
tags: ["Training Techniques"]
short_authors: Sun et al.
---
Recent pretraining models in Chinese neglect two important aspects specific
to the Chinese language: glyph and pinyin, which carry significant syntax and
semantic information for language understanding. In this work, we propose
ChineseBERT, which incorporates both the \{\it glyph\} and \{\it pinyin\}
information of Chinese characters into language model pretraining. The glyph
embedding is obtained based on different fonts of a Chinese character, being
able to capture character semantics from the visual features, and the pinyin
embedding characterizes the pronunciation of Chinese characters, which handles
the highly prevalent heteronym phenomenon in Chinese (the same character has
different pronunciations with different meanings). Pretrained on large-scale
unlabeled Chinese corpus, the proposed ChineseBERT model yields significant
performance boost over baseline models with fewer training steps. The porpsoed
model achieves new SOTA performances on a wide range of Chinese NLP tasks,
including machine reading comprehension, natural language inference, text
classification, sentence pair matching, and competitive performances in named
entity recognition. Code and pretrained models are publicly available at
https://github.com/ShannonAI/ChineseBert.