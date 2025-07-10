---
layout: publication
title: 'Pangu-coder: Program Synthesis With Function-level Language Modeling'
authors: Fenia Christopoulou et al.
conference: Arxiv
year: 2022
citations: 16
bibkey: christopoulou2022pangu
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.11280'}]
tags: [Language Modeling, Model Architecture, Masked Language Model, Reinforcement
    Learning, Pre-Training, Training Techniques]
---
We present PanGu-Coder, a pretrained decoder-only language model adopting the
PanGu-Alpha architecture for text-to-code generation, i.e. the synthesis of
programming language solutions given a natural language problem description. We
train PanGu-Coder using a two-stage strategy: the first stage employs Causal
Language Modelling (CLM) to pre-train on raw programming language data, while
the second stage uses a combination of Causal Language Modelling and Masked
Language Modelling (MLM) training objectives that focus on the downstream task
of text-to-code generation and train on loosely curated pairs of natural
language program definitions and code functions. Finally, we discuss
PanGu-Coder-FT, which is fine-tuned on a combination of competitive programming
problems and code with continuous integration tests. We evaluate PanGu-Coder
with a focus on whether it generates functionally correct programs and
demonstrate that it achieves equivalent or better performance than similarly
sized models, such as CodeX, while attending a smaller context window and
training on less data.