---
layout: publication
title: 'PALM: Pre-training An Autoencoding&autoregressive Language Model For Context-conditioned
  Generation'
authors: Bin Bi et al.
conference: Arxiv
year: 2020
citations: 22
bibkey: bi2020pre
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.07159'}]
tags: [Training Techniques, Transformer, GPT, Pre-Training, Fine-Tuning, BERT, Model
    Architecture]
---
Self-supervised pre-training, such as BERT, MASS and BART, has emerged as a
powerful technique for natural language understanding and generation. Existing
pre-training techniques employ autoencoding and/or autoregressive objectives to
train Transformer-based models by recovering original word tokens from
corrupted text with some masked tokens. The training goals of existing
techniques are often inconsistent with the goals of many language generation
tasks, such as generative question answering and conversational response
generation, for producing new text given context.
  This work presents PALM with a novel scheme that jointly pre-trains an
autoencoding and autoregressive language model on a large unlabeled corpus,
specifically designed for generating new text conditioned on context. The new
scheme alleviates the mismatch introduced by the existing denoising scheme
between pre-training and fine-tuning where generation is more than
reconstructing original text. An extensive set of experiments show that PALM
achieves new state-of-the-art results on a variety of language generation
benchmarks covering generative question answering (Rank 1 on the official MARCO
leaderboard), abstractive summarization on CNN/DailyMail as well as Gigaword,
question generation on SQuAD, and conversational response generation on Cornell
Movie Dialogues.