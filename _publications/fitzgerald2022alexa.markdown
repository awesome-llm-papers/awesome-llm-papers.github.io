---
layout: publication
title: 'Alexa Teacher Model: Pretraining And Distilling Multi-billion-parameter Encoders
  For Natural Language Understanding Systems'
authors: Fitzgerald et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2022
bibkey: fitzgerald2022alexa
citations: 547
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.07808'}]
tags: [Model Architecture, Distillation, Tools, Training Techniques, Efficiency And
    Optimization, BERT, ACL, EMNLP, Datasets]
---
We present results from a large-scale experiment on pretraining encoders with
non-embedding parameter counts ranging from 700M to 9.3B, their subsequent
distillation into smaller models ranging from 17M-170M parameters, and their
application to the Natural Language Understanding (NLU) component of a virtual
assistant system. Though we train using 70% spoken-form data, our teacher
models perform comparably to XLM-R and mT5 when evaluated on the written-form
Cross-lingual Natural Language Inference (XNLI) corpus. We perform a second
stage of pretraining on our teacher models using in-domain data from our
system, improving error rates by 3.86% relative for intent classification and
7.01% relative for slot filling. We find that even a 170M-parameter model
distilled from our Stage 2 teacher model has 2.88% better intent classification
and 7.69% better slot filling error rates when compared to the 2.3B-parameter
teacher trained only on public data (Stage 1), emphasizing the importance of
in-domain data for pretraining. When evaluated offline using labeled NLU data,
our 17M-parameter Stage 2 distilled model outperforms both XLM-R Base (85M
params) and DistillBERT (42M params) by 4.23% to 6.14%, respectively. Finally,
we present results from a full virtual assistant experimentation platform,
where we find that models trained using our pretraining and distillation
pipeline outperform models distilled from 85M-parameter teachers by 3.74%-4.91%
on an automatic measurement of full-system user dissatisfaction.