---
layout: publication
title: Masking As An Efficient Alternative To Finetuning For Pretrained Language Models
authors: "Mengjie Zhao, Tao Lin, Fei Mi, Martin Jaggi, Hinrich Sch\xFCtze"
conference: Arxiv
year: 2020
citations: 26
bibkey: zhao2020masking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.12406'}]
tags: [Masked Language Model, Reinforcement Learning, Model Architecture, BERT]
---
We present an efficient method of utilizing pretrained language models, where
we learn selective binary masks for pretrained weights in lieu of modifying
them through finetuning. Extensive evaluations of masking BERT and RoBERTa on a
series of NLP tasks show that our masking scheme yields performance comparable
to finetuning, yet has a much smaller memory footprint when several tasks need
to be inferred simultaneously. Through intrinsic evaluations, we show that
representations computed by masked language models encode information necessary
for solving downstream tasks. Analyzing the loss landscape, we show that
masking and finetuning produce models that reside in minima that can be
connected by a line segment with nearly constant test accuracy. This confirms
that masking can be utilized as an efficient alternative to finetuning.