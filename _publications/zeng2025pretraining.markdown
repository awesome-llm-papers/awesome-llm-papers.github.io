---
layout: publication
title: Pretraining Language Models To Ponder In Continuous Space
authors: Zeng et al.
conference: Computer Speech &amp; Language
year: 2025
bibkey: zeng2025pretraining
citations: 217
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.20674'}]
tags: [Training Techniques, GPT, Evaluation, Model Architecture, Language Modeling,
  Datasets]
---
Humans ponder before articulating complex sentence elements, enabling deeper cognitive processing through focused effort. In this work, we introduce this pondering process into language models by repeatedly invoking the forward process within a single token generation step. During pondering, instead of generating an actual token sampled from the prediction distribution, the model ponders by yielding a weighted sum of all token embeddings according to the predicted token distribution. The generated embedding is then fed back as input for another forward pass. We show that the model can learn to ponder in this way through self-supervised learning, without any human annotations. Experiments across three widely used open-source architectures-GPT-2, Pythia, and LLaMA-and extensive downstream task evaluations demonstrate the effectiveness and generality of our method. For language modeling tasks, pondering language models achieve performance comparable to vanilla models with twice the number of parameters. On 9 downstream benchmarks, our pondering-enhanced Pythia models significantly outperform the official Pythia models. Notably, PonderingPythia-2.8B surpasses Pythia-6.9B, and PonderingPythia-1B is comparable to TinyLlama-1.1B, which is trained on 10 times more data. The code is available at https://github.com/LUMIA-Group/PonderingLM.