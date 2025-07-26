---
layout: publication
title: Fast Domain Adaptation For Neural Machine Translation
authors: Markus Freitag, Yaser Al-onaizan
conference: Arxiv
year: 2016
bibkey: freitag2016fast
citations: 181
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.06897'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Markus Freitag, Yaser Al-onaizan
---
Neural Machine Translation (NMT) is a new approach for automatic translation
of text from one human language into another. The basic concept in NMT is to
train a large Neural Network that maximizes the translation performance on a
given parallel corpus. NMT is gaining popularity in the research community
because it outperformed traditional SMT approaches in several translation tasks
at WMT and other evaluation tasks/benchmarks at least for some language pairs.
However, many of the enhancements in SMT over the years have not been
incorporated into the NMT framework. In this paper, we focus on one such
enhancement namely domain adaptation. We propose an approach for adapting a NMT
system to a new domain. The main idea behind domain adaptation is that the
availability of large out-of-domain training data and a small in-domain
training data. We report significant gains with our proposed method in both
automatic metrics and a human subjective evaluation metric on two language
pairs. With our adaptation method, we show large improvement on the new domain
while the performance of our general domain only degrades slightly. In
addition, our approach is fast enough to adapt an already trained system to a
new domain within few hours without the need to retrain the NMT model on the
combined data which usually takes several days/weeks depending on the volume of
the data.