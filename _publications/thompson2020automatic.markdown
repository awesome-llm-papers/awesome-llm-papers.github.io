---
layout: publication
title: Automatic Machine Translation Evaluation In Many Languages Via Zero-shot Paraphrasing
authors: Brian Thompson, Matt Post
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: thompson2020automatic
citations: 128
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14564'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Brian Thompson, Matt Post
---
We frame the task of machine translation evaluation as one of scoring machine
translation output with a sequence-to-sequence paraphraser, conditioned on a
human reference. We propose training the paraphraser as a multilingual NMT
system, treating paraphrasing as a zero-shot translation task (e.g., Czech to
Czech). This results in the paraphraser's output mode being centered around a
copy of the input sequence, which represents the best case scenario where the
MT system output matches a human reference. Our method is simple and intuitive,
and does not require human judgements for training. Our single model (trained
in 39 languages) outperforms or statistically ties with all prior metrics on
the WMT 2019 segment-level shared metrics task in all languages (excluding
Gujarati where the model had no training data). We also explore using our model
for the task of quality estimation as a metric--conditioning on the source
instead of the reference--and find that it significantly outperforms every
submission to the WMT 2019 shared task on quality estimation in every language
pair.