---
layout: publication
title: Multi-view Sequence-to-sequence Models With Conversational Structure For Abstractive
  Dialogue Summarization
authors: Chen Jiaao, Yang Diyi
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: chen2020multi
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.01672'}]
tags: [EMNLP, Attention Mechanism, Alt, Evaluation, Model Architecture, Datasets]
---
Text summarization is one of the most challenging and interesting problems in
NLP. Although much attention has been paid to summarizing structured text like
news reports or encyclopedia articles, summarizing conversations---an essential
part of human-human/machine interaction where most important pieces of
information are scattered across various utterances of different
speakers---remains relatively under-investigated. This work proposes a
multi-view sequence-to-sequence model by first extracting conversational
structures of unstructured daily chats from different views to represent
conversations and then utilizing a multi-view decoder to incorporate different
views to generate dialogue summaries. Experiments on a large-scale dialogue
summarization corpus demonstrated that our methods significantly outperformed
previous state-of-the-art models via both automatic evaluations and human
judgment. We also discussed specific challenges that current approaches faced
with this task. We have publicly released our code at
https://github.com/GT-SALT/Multi-View-Seq2Seq.