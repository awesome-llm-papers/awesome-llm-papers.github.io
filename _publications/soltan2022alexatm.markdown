---
layout: publication
title: 'Alexatm 20B: Few-shot Learning Using A Large-scale Multilingual Seq2seq Model'
authors: Saleh Soltan et al.
conference: Arxiv
year: 2022
citations: 33
bibkey: soltan2022alexatm
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2208.01448v2'}]
tags: [Language Modeling, Model Architecture, GPT, Few-Shot, Reinforcement Learning,
  Training Techniques]
---
In this work, we demonstrate that multilingual large-scale
sequence-to-sequence (seq2seq) models, pre-trained on a mixture of denoising
and Causal Language Modeling (CLM) tasks, are more efficient few-shot learners
than decoder-only models on various tasks. In particular, we train a 20 billion
parameter multilingual seq2seq model called Alexa Teacher Model (AlexaTM 20B)
and show that it achieves state-of-the-art (SOTA) performance on 1-shot
summarization tasks, outperforming a much larger 540B PaLM decoder model.
AlexaTM 20B also achieves SOTA in 1-shot machine translation, especially for
low-resource languages, across almost all language pairs supported by the model
(Arabic, English, French, German, Hindi, Italian, Japanese, Marathi,
Portuguese, Spanish, Tamil, and Telugu) on Flores-101 dataset. We also show in
zero-shot setting, AlexaTM 20B outperforms GPT3 (175B) on SuperGLUE and SQuADv2
datasets and provides SOTA performance on multilingual tasks such as XNLI,
XCOPA, Paws-X, and XWinograd. Overall, our results present a compelling case
for seq2seq models as a powerful alternative to decoder-only models for
Large-scale Language Model (LLM) training.