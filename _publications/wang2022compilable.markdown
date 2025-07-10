---
layout: publication
title: Compilable Neural Code Generation With Compiler Feedback
authors: Xin Wang et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2022
citations: 15
bibkey: wang2022compilable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.05132'}]
tags: [Language Modeling, Model Architecture, GPT, Fine-Tuning, RAG, Training Techniques]
---
Automatically generating compilable programs with (or without) natural
language descriptions has always been a touchstone problem for computational
linguistics and automated software engineering. Existing deep-learning
approaches model code generation as text generation, either constrained by
grammar structures in decoder, or driven by pre-trained language models on
large-scale code corpus (e.g., CodeGPT, PLBART, and CodeT5). However, few of
them account for compilability of the generated programs. To improve
compilability of the generated programs, this paper proposes COMPCODER, a
three-stage pipeline utilizing compiler feedback for compilable code
generation, including language model fine-tuning, compilability reinforcement,
and compilability discrimination. Comprehensive experiments on two code
generation tasks demonstrate the effectiveness of our proposed approach,
improving the success rate of compilation from 44.18 to 89.18 in code
completion on average and from 70.3 to 96.2 in text-to-code generation,
respectively, when comparing with the state-of-the-art CodeGPT.