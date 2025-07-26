---
layout: publication
title: 'CPT: A Pre-trained Unbalanced Transformer For Both Chinese Language Understanding
  And Generation'
authors: Yunfan Shao, Zhichao Geng, Yitao Liu, Junqi Dai, Hang Yan, Fei Yang, Li Zhe,
  Hujun Bao, Xipeng Qiu
conference: Science China Information Sciences
year: 2024
bibkey: shao2021cpt
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.05729'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Shao et al.
---
In this paper, we take the advantage of previous pre-trained models (PTMs)
and propose a novel Chinese Pre-trained Unbalanced Transformer (CPT). Different
from previous Chinese PTMs, CPT is designed to utilize the shared knowledge
between natural language understanding (NLU) and natural language generation
(NLG) to boost the performance. CPT consists of three parts: a shared encoder,
an understanding decoder, and a generation decoder. Two specific decoders with
a shared encoder are pre-trained with masked language modeling (MLM) and
denoising auto-encoding (DAE) tasks, respectively. With the partially shared
architecture and multi-task pre-training, CPT can (1) learn specific knowledge
of both NLU or NLG tasks with two decoders and (2) be fine-tuned flexibly that
fully exploits the potential of the model. Moreover, the unbalanced Transformer
saves the computational and storage cost, which makes CPT competitive and
greatly accelerates the inference of text generation. Experimental results on a
wide range of Chinese NLU and NLG tasks show the effectiveness of CPT.