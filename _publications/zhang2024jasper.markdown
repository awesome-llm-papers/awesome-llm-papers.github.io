---
layout: publication
title: 'Jasper And Stella: Distillation Of SOTA Embedding Models'
authors: Zhang et al.
conference: Proceedings of the 32nd ACM International Conference on Information and
  Knowledge Management
year: 2024
bibkey: zhang2024jasper
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.19048'}]
tags: [RAG, Training Techniques, Distillation, Tools, Evaluation, CIKM, Efficiency
    And Optimization, Reinforcement Learning, Applications, Datasets]
---
A crucial component in many deep learning applications, such as Frequently
Asked Questions (FAQ) and Retrieval-Augmented Generation (RAG), is dense
retrieval. In this process, embedding models transform raw text into numerical
vectors. However, the embedding models that currently excel on text embedding
benchmarks, like the Massive Text Embedding Benchmark (MTEB), often have
numerous parameters and high vector dimensionality. This poses challenges for
their application in real-world scenarios. To address this issue, we propose a
novel multi-stage distillation framework that enables a smaller student
embedding model to distill multiple larger teacher embedding models through
three carefully designed losses. Meanwhile, we utilize Matryoshka
Representation Learning (MRL) to reduce the vector dimensionality of the
student embedding model effectively. Our student model named Jasper with 2
billion parameters, built upon the Stella embedding model, obtained the No.3
position on the MTEB leaderboard (as of December 24, 2024), achieving an
average 71.54 score across 56 datasets. We have released the model and data on
the Hugging Face Hub
(https://huggingface.co/infgrad/jasper_en_vision_language_v1)
(https://huggingface.co/datasets/infgrad/jasper_text_distill_dataset), and the
training codes are available in this project repository
(https://github.com/NLPJCL/RAG-Retrieval).