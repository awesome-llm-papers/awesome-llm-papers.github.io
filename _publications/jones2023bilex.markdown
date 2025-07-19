---
layout: publication
title: 'Bilex Rx: Lexical Data Augmentation For Massively Multilingual Machine Translation'
authors: Jones et al.
conference: Proceedings of the 2019 Conference of the North
year: 2023
bibkey: jones2023bilex
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.15265'}]
tags: [Tools, Reinforcement Learning]
---
Neural machine translation (NMT) has progressed rapidly over the past several
years, and modern models are able to achieve relatively high quality using only
monolingual text data, an approach dubbed Unsupervised Machine Translation
(UNMT). However, these models still struggle in a variety of ways, including
aspects of translation that for a human are the easiest - for instance,
correctly translating common nouns. This work explores a cheap and abundant
resource to combat this problem: bilingual lexica. We test the efficacy of
bilingual lexica in a real-world set-up, on 200-language translation models
trained on web-crawled text. We present several findings: (1) using lexical
data augmentation, we demonstrate sizable performance gains for unsupervised
translation; (2) we compare several families of data augmentation,
demonstrating that they yield similar improvements, and can be combined for
even greater improvements; (3) we demonstrate the importance of carefully
curated lexica over larger, noisier ones, especially with larger models; and
(4) we compare the efficacy of multilingual lexicon data versus
human-translated parallel data. Finally, we open-source GATITOS (available at
https://github.com/google-research/url-nlp/tree/main/gatitos), a new
multilingual lexicon for 26 low-resource languages, which had the highest
performance among lexica in our experiments.