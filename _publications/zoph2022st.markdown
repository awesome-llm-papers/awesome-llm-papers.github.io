---
layout: publication
title: 'St-moe: Designing Stable And Transferable Sparse Expert Models'
authors: Barret Zoph et al.
conference: Arxiv
year: 2022
citations: 33
bibkey: zoph2022st
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.08906'}]
tags: [Security, Model Architecture, Transformer, Fine-Tuning, Training Techniques]
---
Scale has opened new frontiers in natural language processing -- but at a
high cost. In response, Mixture-of-Experts (MoE) and Switch Transformers have
been proposed as an energy efficient path to even larger and more capable
language models. But advancing the state-of-the-art across a broad set of
natural language tasks has been hindered by training instabilities and
uncertain quality during fine-tuning. Our work focuses on these issues and acts
as a design guide. We conclude by scaling a sparse model to 269B parameters,
with a computational cost comparable to a 32B dense encoder-decoder Transformer
(Stable and Transferable Mixture-of-Experts or ST-MoE-32B). For the first time,
a sparse model achieves state-of-the-art performance in transfer learning,
across a diverse set of tasks including reasoning (SuperGLUE, ARC Easy, ARC
Challenge), summarization (XSum, CNN-DM), closed book question answering
(WebQA, Natural Questions), and adversarially constructed tasks (Winogrande,
ANLI R3).