---
layout: publication
title: 'Commitbert: Commit Message Generation Using Pre-trained Programming Language
  Model'
authors: Tae-hwan Jung
conference: Proceedings of the 1st Workshop on Natural Language Processing for Programming
  (NLP4Prog 2021)
year: 2021
citations: 16
bibkey: jung2021commit
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.14242'}, {name: Code,
    url: 'https://github.com/graykode/commit-autosuggestions'}]
tags: [Has Code, Model Architecture, Reinforcement Learning, Training Techniques,
  BERT]
---
Commit message is a document that summarizes source code changes in natural
language. A good commit message clearly shows the source code changes, so this
enhances collaboration between developers. Therefore, our work is to develop a
model that automatically writes the commit message.
  To this end, we release 345K datasets consisting of code modification and
commit messages in six programming languages (Python, PHP, Go, Java,
JavaScript, and Ruby). Similar to the neural machine translation (NMT) model,
using our dataset, we feed the code modification to the encoder input and the
commit message to the decoder input and measure the result of the generated
commit message with BLEU-4.
  Also, we propose the following two training methods to improve the result of
generating the commit message: (1) A method of preprocessing the input to feed
the code modification to the encoder input. (2) A method that uses an initial
weight suitable for the code domain to reduce the gap in contextual
representation between programming language (PL) and natural language (NL).
Training code, dataset, and pre-trained weights are available at
https://github.com/graykode/commit-autosuggestions