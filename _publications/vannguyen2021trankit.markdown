---
layout: publication
title: 'Trankit: A Light-weight Transformer-based Toolkit For Multilingual Natural
  Language Processing'
authors: Minh van Nguyen, Viet Dac Lai, Amir Pouran Ben Veyseh, Thien Huu Nguyen
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: System Demonstrations'
year: 2021
bibkey: vannguyen2021trankit
citations: 89
additional_links: [{name: Code, url: 'https://github.com/nlp-uoregon/trankit'}, {
    name: Code, url: 'http://nlp.uoregon.edu/trankit'}, {name: Code, url: 'https://youtu.be/q0KGP3zGjGc'},
  {name: Paper, url: 'https://arxiv.org/abs/2101.03289'}]
tags: ["EACL", "Has Code", "Model Architecture"]
short_authors: Nguyen et al.
---
We introduce Trankit, a light-weight Transformer-based Toolkit for
multilingual Natural Language Processing (NLP). It provides a trainable
pipeline for fundamental NLP tasks over 100 languages, and 90 pretrained
pipelines for 56 languages. Built on a state-of-the-art pretrained language
model, Trankit significantly outperforms prior multilingual NLP pipelines over
sentence segmentation, part-of-speech tagging, morphological feature tagging,
and dependency parsing while maintaining competitive performance for
tokenization, multi-word token expansion, and lemmatization over 90 Universal
Dependencies treebanks. Despite the use of a large pretrained transformer, our
toolkit is still efficient in memory usage and speed. This is achieved by our
novel plug-and-play mechanism with Adapters where a multilingual pretrained
transformer is shared across pipelines for different languages. Our toolkit
along with pretrained models and code are publicly available at:
https://github.com/nlp-uoregon/trankit. A demo website for our toolkit is also
available at: http://nlp.uoregon.edu/trankit. Finally, we create a demo video
for Trankit at: https://youtu.be/q0KGP3zGjGc.