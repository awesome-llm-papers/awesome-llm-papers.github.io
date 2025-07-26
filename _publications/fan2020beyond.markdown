---
layout: publication
title: Beyond English-centric Multilingual Machine Translation
authors: Angela Fan, Shruti Bhosale, Holger Schwenk, Zhiyi Ma, Ahmed El-kishky, Siddharth
  Goyal, Mandeep Baines, Onur Celebi, Guillaume Wenzek, Vishrav Chaudhary, Naman Goyal,
  Tom Birch, Vitaliy Liptchinsky, Sergey Edunov, Edouard Grave, Michael Auli, Armand
  Joulin
conference: Arxiv
year: 2020
bibkey: fan2020beyond
citations: 413
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11125'}]
tags: ["Datasets", "Evaluation", "Training Techniques"]
short_authors: Fan et al.
---
Existing work in translation demonstrated the potential of massively
multilingual machine translation by training a single model able to translate
between any pair of languages. However, much of this work is English-Centric by
training only on data which was translated from or to English. While this is
supported by large sources of training data, it does not reflect translation
needs worldwide. In this work, we create a true Many-to-Many multilingual
translation model that can translate directly between any pair of 100
languages. We build and open source a training dataset that covers thousands of
language directions with supervised data, created through large-scale mining.
Then, we explore how to effectively increase model capacity through a
combination of dense scaling and language-specific sparse parameters to create
high quality models. Our focus on non-English-Centric models brings gains of
more than 10 BLEU when directly translating between non-English directions
while performing competitively to the best single systems of WMT. We
open-source our scripts so that others may reproduce the data, evaluation, and
final M2M-100 model.