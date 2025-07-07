---
layout: publication
title: Knowledge Neurons In Pretrained Transformers
authors: Damai Dai et al.
conference: Arxiv
year: 2021
citations: 47
bibkey: dai2021knowledge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08696'}, {name: Code,
    url: 'https://github.com/Hunter-DDM/knowledge-neurons'}]
tags: [Training Techniques, Transformer, RAG, Fine-Tuning, BERT, Has Code, Model Architecture]
---
Large-scale pretrained language models are surprisingly good at recalling
factual knowledge presented in the training corpus. In this paper, we present
preliminary studies on how factual knowledge is stored in pretrained
Transformers by introducing the concept of knowledge neurons. Specifically, we
examine the fill-in-the-blank cloze task for BERT. Given a relational fact, we
propose a knowledge attribution method to identify the neurons that express the
fact. We find that the activation of such knowledge neurons is positively
correlated to the expression of their corresponding facts. In our case studies,
we attempt to leverage knowledge neurons to edit (such as update, and erase)
specific factual knowledge without fine-tuning. Our results shed light on
understanding the storage of knowledge within pretrained Transformers. The code
is available at https://github.com/Hunter-DDM/knowledge-neurons.