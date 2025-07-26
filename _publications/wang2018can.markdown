---
layout: publication
title: Can You Tell Me How To Get Past Sesame Street? Sentence-level Pretraining Beyond
  Language Modeling
authors: Alex Wang, Jan Hula, Patrick Xia, Raghavendra Pappagari, R. Thomas Mccoy,
  Roma Patel, Najoung Kim, Ian Tenney, Yinghui Huang, Katherin Yu, Shuning Jin, Berlin
  Chen, Benjamin van Durme, Edouard Grave, Ellie Pavlick, Samuel R. Bowman
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: wang2018can
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.10860'}]
tags: ["Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
Natural language understanding has recently seen a surge of progress with the
use of sentence encoders like ELMo (Peters et al., 2018a) and BERT (Devlin et
al., 2019) which are pretrained on variants of language modeling. We conduct
the first large-scale systematic study of candidate pretraining tasks,
comparing 19 different tasks both as alternatives and complements to language
modeling. Our primary results support the use language modeling, especially
when combined with pretraining on additional labeled-data tasks. However, our
results are mixed across pretraining tasks and show some concerning trends: In
ELMo's pretrain-then-freeze paradigm, random baselines are worryingly strong
and results vary strikingly across target tasks. In addition, fine-tuning BERT
on an intermediate task often negatively impacts downstream transfer. In a more
positive trend, we see modest gains from multitask training, suggesting the
development of more sophisticated multitask and transfer learning techniques as
an avenue for further research.