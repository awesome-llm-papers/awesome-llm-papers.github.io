---
layout: publication
title: 'Memorization Without Overfitting: Analyzing The Training Dynamics Of Large
  Language Models'
authors: Kushal Tirumala, Aram H. Markosyan, Luke Zettlemoyer, Armen Aghajanyan
conference: Arxiv
year: 2022
citations: 41
bibkey: tirumala2022memorization
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.10770'}]
tags: [Masked Language Model, Training Techniques, Reinforcement Learning, BERT, Language
    Modeling]
---
Despite their wide adoption, the underlying training and memorization
dynamics of very large language models is not well understood. We empirically
study exact memorization in causal and masked language modeling, across model
sizes and throughout the training process. We measure the effects of dataset
size, learning rate, and model size on memorization, finding that larger
language models memorize training data faster across all settings.
Surprisingly, we show that larger models can memorize a larger portion of the
data before over-fitting and tend to forget less throughout the training
process. We also analyze the memorization dynamics of different parts of speech
and find that models memorize nouns and numbers first; we hypothesize and
provide empirical evidence that nouns and numbers act as a unique identifier
for memorizing individual training examples. Together, these findings present
another piece of the broader puzzle of trying to understand what actually
improves as models get bigger.