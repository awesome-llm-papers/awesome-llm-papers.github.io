---
layout: publication
title: 'Robertuito: A Pre-trained Language Model For Social Media Text In Spanish'
authors: "Juan Manuel P\xE9rez, Dami\xE1n A. Furman, Laura Alonso Alemany, Franco\
  \ Luque"
conference: Arxiv
year: 2021
citations: 29
bibkey: "p\xE9rez2021pre"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.09453'}]
tags: [Model Architecture, Transformer, Fine-Tuning, Pre-Training, BERT, Training
    Techniques, Evaluation]
---
Since BERT appeared, Transformer language models and transfer learning have
become state-of-the-art for Natural Language Understanding tasks. Recently,
some works geared towards pre-training specially-crafted models for particular
domains, such as scientific papers, medical documents, user-generated texts,
among others. These domain-specific models have been shown to improve
performance significantly in most tasks. However, for languages other than
English such models are not widely available.
  In this work, we present RoBERTuito, a pre-trained language model for
user-generated text in Spanish, trained on over 500 million tweets. Experiments
on a benchmark of tasks involving user-generated text showed that RoBERTuito
outperformed other pre-trained language models in Spanish. In addition to this,
our model achieves top results for some English-Spanish tasks of the Linguistic
Code-Switching Evaluation benchmark (LinCE) and has also competitive
performance against monolingual models in English tasks. To facilitate further
research, we make RoBERTuito publicly available at the HuggingFace model hub
together with the dataset used to pre-train it.