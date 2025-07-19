---
layout: publication
title: 'Marian: Cost-effective High-quality Neural Machine Translation In C++'
authors: Junczys-dowmunt et al.
conference: Proceedings of the 2nd Workshop on Neural Machine Translation and Generation
year: 2018
bibkey: junczysdowmunt2018marian
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.12096'}]
tags: [RAG, Training Techniques, Attention Mechanism, Transformer, Model Architecture]
---
This paper describes the submissions of the "Marian" team to the WNMT 2018
shared task. We investigate combinations of teacher-student training,
low-precision matrix products, auto-tuning and other methods to optimize the
Transformer model on GPU and CPU. By further integrating these methods with the
new averaging attention networks, a recently introduced faster Transformer
variant, we create a number of high-quality, high-performance models on the GPU
and CPU, dominating the Pareto frontier for this shared task.