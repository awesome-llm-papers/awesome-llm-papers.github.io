---
layout: publication
title: 'Gpt-neox-20b: An Open-source Autoregressive Language Model'
authors: Sid Black, Stella Biderman, Eric Hallahan, Quentin Anthony, Leo Gao, Laurence
  Golding, Horace He, Connor Leahy, Kyle Mcdonell, Jason Phang, Michael Pieler, Usvsn
  Sai Prashanth, Shivanshu Purohit, Laria Reynolds, Jonathan Tow, Ben Wang, Samuel
  Weinbach
conference: 'Proceedings of BigScience Episode #5 -- Workshop on Challenges &amp;
  Perspectives in Creating Large Language Models'
year: 2022
bibkey: black2022gpt
citations: 294
additional_links: [{name: Code, url: 'https://github.com/EleutherAI/gpt-neox'}, {
    name: Paper, url: 'https://arxiv.org/abs/2204.06745'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Black et al.
---
We introduce GPT-NeoX-20B, a 20 billion parameter autoregressive language
model trained on the Pile, whose weights will be made freely and openly
available to the public through a permissive license. It is, to the best of our
knowledge, the largest dense autoregressive model that has publicly available
weights at the time of submission. In this work, we describe \model\{\}'s
architecture and training and evaluate its performance on a range of
language-understanding, mathematics, and knowledge-based tasks. We find that
GPT-NeoX-20B is a particularly powerful few-shot reasoner and gains far more in
performance when evaluated five-shot than similarly sized GPT-3 and FairSeq
models. We open-source the training and evaluation code, as well as the model
weights, at https://github.com/EleutherAI/gpt-neox.