---
layout: publication
title: A Multilingual Modeling Method For Span-extraction Reading Comprehension
authors: Wu et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2021
bibkey: wu2021multilingual
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.14880'}]
tags: [Training Techniques, EMNLP, Attention Mechanism, Alt, Tools, Transformer, BERT,
  Model Architecture, Datasets]
---
Span-extraction reading comprehension models have made tremendous advances
enabled by the availability of large-scale, high-quality training datasets.
Despite such rapid progress and widespread application, extractive reading
comprehension datasets in languages other than English remain scarce, and
creating such a sufficient amount of training data for each language is costly
and even impossible. An alternative to creating large-scale high-quality
monolingual span-extraction training datasets is to develop multilingual
modeling approaches and systems which can transfer to the target language
without requiring training data in that language. In this paper, in order to
solve the scarce availability of extractive reading comprehension training data
in the target language, we propose a multilingual extractive reading
comprehension approach called XLRC by simultaneously modeling the existing
extractive reading comprehension training data in a multilingual environment
using self-adaptive attention and multilingual attention. Specifically, we
firstly construct multilingual parallel corpora by translating the existing
extractive reading comprehension datasets (i.e., CMRC 2018) from the target
language (i.e., Chinese) into different language families (i.e., English).
Secondly, to enhance the final target representation, we adopt self-adaptive
attention (SAA) to combine self-attention and inter-attention to extract the
semantic relations from each pair of the target and source languages.
Furthermore, we propose multilingual attention (MLA) to learn the rich
knowledge from various language families. Experimental results show that our
model outperforms the state-of-the-art baseline (i.e., RoBERTa_Large) on the
CMRC 2018 task, which demonstrate the effectiveness of our proposed
multi-lingual modeling approach and show the potentials in multilingual NLP
tasks.