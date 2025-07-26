---
layout: publication
title: Large-scale Multilingual Speech Recognition With A Streaming End-to-end Model
authors: Anjuli Kannan, Arindrima Datta, Tara N. Sainath, Eugene Weinstein, Bhuvana
  Ramabhadran, Yonghui Wu, Ankur Bapna, Zhifeng Chen, Seungji Lee
conference: Interspeech 2019
year: 2019
bibkey: kannan2019large
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.05330'}]
tags: ["Applications", "INTERSPEECH", "Training Techniques"]
short_authors: Kannan et al.
---
Multilingual end-to-end (E2E) models have shown great promise in expansion of
automatic speech recognition (ASR) coverage of the world's languages. They have
shown improvement over monolingual systems, and have simplified training and
serving by eliminating language-specific acoustic, pronunciation, and language
models. This work presents an E2E multilingual system which is equipped to
operate in low-latency interactive applications, as well as handle a key
challenge of real world data: the imbalance in training data across languages.
Using nine Indic languages, we compare a variety of techniques, and find that a
combination of conditioning on a language vector and training language-specific
adapter layers produces the best model. The resulting E2E multilingual model
achieves a lower word error rate (WER) than both monolingual E2E models (eight
of nine languages) and monolingual conventional systems (all nine languages).