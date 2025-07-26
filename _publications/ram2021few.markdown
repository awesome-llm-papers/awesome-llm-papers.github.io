---
layout: publication
title: Few-shot Question Answering By Pretraining Span Selection
authors: Ori Ram, Yuval Kirstain, Jonathan Berant, Amir Globerson, Omer Levy
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: ram2021few
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.00438'}]
tags: ["Few-Shot"]
short_authors: Ram et al.
---
In several question answering benchmarks, pretrained models have reached
human parity through fine-tuning on an order of 100,000 annotated questions and
answers. We explore the more realistic few-shot setting, where only a few
hundred training examples are available, and observe that standard models
perform poorly, highlighting the discrepancy between current pretraining
objectives and question answering. We propose a new pretraining scheme tailored
for question answering: recurring span selection. Given a passage with multiple
sets of recurring spans, we mask in each set all recurring spans but one, and
ask the model to select the correct span in the passage for each masked span.
Masked spans are replaced with a special token, viewed as a question
representation, that is later used during fine-tuning to select the answer
span. The resulting model obtains surprisingly good results on multiple
benchmarks (e.g., 72.7 F1 on SQuAD with only 128 training examples), while
maintaining competitive performance in the high-resource setting.