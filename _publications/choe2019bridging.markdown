---
layout: publication
title: Bridging The Gap For Tokenizer-free Language Models
authors: Dokook Choe, Rami Al-rfou, Mandy Guo, Heeyoung Lee, Noah Constant
conference: Arxiv
year: 2019
citations: 16
bibkey: choe2019bridging
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.10322'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Tokenization]
---
Purely character-based language models (LMs) have been lagging in quality on
large scale datasets, and current state-of-the-art LMs rely on word
tokenization. It has been assumed that injecting the prior knowledge of a
tokenizer into the model is essential to achieving competitive results. In this
paper, we show that contrary to this conventional wisdom, tokenizer-free LMs
with sufficient capacity can achieve competitive performance on a large scale
dataset. We train a vanilla transformer network with 40 self-attention layers
on the One Billion Word (lm1b) benchmark and achieve a new state of the art for
tokenizer-free LMs, pushing these models to be on par with their word-based
counterparts.