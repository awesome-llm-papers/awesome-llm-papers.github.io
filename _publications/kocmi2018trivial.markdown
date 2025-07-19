---
layout: publication
title: Trivial Transfer Learning For Low-resource Neural Machine Translation
authors: "Kocmi Tom, Bojar Ond\u0159ej"
conference: 'Proceedings of the Third Conference on Machine Translation: Research
  Papers'
year: 2018
bibkey: kocmi2018trivial
citations: 157
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.00357'}]
tags: [Datasets, Training Techniques, Fine Tuning, WMT]
---
Transfer learning has been proven as an effective technique for neural
machine translation under low-resource conditions. Existing methods require a
common target language, language relatedness, or specific training tricks and
regimes. We present a simple transfer learning method, where we first train a
"parent" model for a high-resource language pair and then continue the training
on a lowresource pair only by replacing the training corpus. This "child" model
performs significantly better than the baseline trained for lowresource pair
only. We are the first to show this for targeting different languages, and we
observe the improvements even for unrelated languages with different alphabets.