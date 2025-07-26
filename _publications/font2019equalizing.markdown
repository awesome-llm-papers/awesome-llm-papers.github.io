---
layout: publication
title: Equalizing Gender Biases In Neural Machine Translation With Word Embeddings
  Techniques
authors: "Joel Escud\xE9 Font, Marta R. Costa-juss\xE0"
conference: Proceedings of the First Workshop on Gender Bias in Natural Language Processing
year: 2019
bibkey: font2019equalizing
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.03116'}]
tags: ["Ethics & Fairness", "Evaluation"]
short_authors: "Joel Escud\xE9 Font, Marta R. Costa-juss\xE0"
---
Neural machine translation has significantly pushed forward the quality of
the field. However, there are remaining big issues with the output translations
and one of them is fairness. Neural models are trained on large text corpora
which contain biases and stereotypes. As a consequence, models inherit these
social biases. Recent methods have shown results in reducing gender bias in
other natural language processing tools such as word embeddings. We take
advantage of the fact that word embeddings are used in neural machine
translation to propose a method to equalize gender biases in neural machine
translation using these representations. Specifically, we propose, experiment
and analyze the integration of two debiasing techniques over GloVe embeddings
in the Transformer translation architecture. We evaluate our proposed system on
the WMT English-Spanish benchmark task, showing gains up to one BLEU point. As
for the gender bias evaluation, we generate a test set of occupations and we
show that our proposed system learns to equalize existing biases from the
baseline system.