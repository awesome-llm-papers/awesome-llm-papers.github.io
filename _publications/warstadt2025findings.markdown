---
layout: publication
title: 'Findings Of The Babylm Challenge: Sample-efficient Pretraining On Developmentally
  Plausible Corpora'
authors: Alex Warstadt et al.
conference: Proceedings of the BabyLM Challenge at the 27th Conference on Computational
  Natural Language Learning
year: 2025
citations: 18
bibkey: warstadt2025findings
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.08165'}]
tags: [BERT, Training Techniques, Model Architecture, Evaluation]
---
Children can acquire language from less than 100 million words of input.
Large language models are far less data-efficient: they typically require 3 or
4 orders of magnitude more data and still do not perform as well as humans on
many evaluations. These intensive resource demands limit the ability of
researchers to train new models and use existing models as developmentally
plausible cognitive models. The BabyLM Challenge is a communal effort in which
participants compete to optimize language model training on a fixed data
budget. Submissions are compared on various evaluation tasks targeting
grammatical ability, downstream task performance, and generalization.
Participants can submit to up to three tracks with progressively looser data
restrictions. From over 30 submissions, we extract concrete recommendations on
how best to train data-efficient language models, and on where future efforts
should (and perhaps should not) focus. The winning submissions using the
LTG-BERT architecture (Samuel et al., 2023) outperformed models trained on
trillions of words. Other submissions achieved strong results through training
on shorter input sequences or training a student model on a pretrained teacher.
Curriculum learning attempts, which accounted for a large number of
submissions, were largely unsuccessful, though some showed modest improvements.