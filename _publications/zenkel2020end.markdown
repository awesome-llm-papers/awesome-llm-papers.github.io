---
layout: publication
title: End-to-end Neural Word Alignment Outperforms GIZA++
authors: Thomas Zenkel, Joern Wuebker, John Denero
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zenkel2020end
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14675'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Thomas Zenkel, Joern Wuebker, John Denero
---
Word alignment was once a core unsupervised learning task in natural language
processing because of its essential role in training statistical machine
translation (MT) models. Although unnecessary for training neural MT models,
word alignment still plays an important role in interactive applications of
neural machine translation, such as annotation transfer and lexicon injection.
While statistical MT methods have been replaced by neural approaches with
superior performance, the twenty-year-old GIZA++ toolkit remains a key
component of state-of-the-art word alignment systems. Prior work on neural word
alignment has only been able to outperform GIZA++ by using its output during
training. We present the first end-to-end neural word alignment method that
consistently outperforms GIZA++ on three data sets. Our approach repurposes a
Transformer model trained for supervised translation to also serve as an
unsupervised word alignment model in a manner that is tightly integrated and
does not affect translation quality.