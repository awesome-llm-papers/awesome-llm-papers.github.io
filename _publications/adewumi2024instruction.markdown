---
layout: publication
title: Instruction Makes A Difference
authors: Adewumi et al.
conference: TESOL Quarterly
year: 2024
bibkey: adewumi2024instruction
citations: 567
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.00453'}]
tags: [Training Techniques, Evaluation, Reinforcement Learning, Fine Tuning, Datasets]
---
We introduce Instruction Document Visual Question Answering (iDocVQA) dataset
and Large Language Document (LLaDoc) model, for training Language-Vision (LV)
models for document analysis and predictions on document images, respectively.
Usually, deep neural networks for the DocVQA task are trained on datasets
lacking instructions. We show that using instruction-following datasets
improves performance. We compare performance across document-related datasets
using the recent state-of-the-art (SotA) Large Language and Vision Assistant
(LLaVA)1.5 as the base model. We also evaluate the performance of the derived
models for object hallucination using the Polling-based Object Probing
Evaluation (POPE) dataset. The results show that instruction-tuning performance
ranges from 11X to 32X of zero-shot performance and from 0.1% to 4.2% over
non-instruction (traditional task) finetuning. Despite the gains, these still
fall short of human performance (94.36%), implying there's much room for
improvement.