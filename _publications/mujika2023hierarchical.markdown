---
layout: publication
title: Hierarchical Attention Encoder Decoder
authors: Mujika Asier
conference: Neurocomputing
year: 2023
bibkey: mujika2023hierarchical
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.01070'}]
tags: [Training Techniques, Attention Mechanism, GPT, Model Architecture, Language
    Modeling, Reinforcement Learning, Applications]
---
Recent advances in large language models have shown that autoregressive
modeling can generate complex and novel sequences that have many real-world
applications. However, these models must generate outputs autoregressively,
which becomes time-consuming when dealing with long sequences. Hierarchical
autoregressive approaches that compress data have been proposed as a solution,
but these methods still generate outputs at the original data frequency,
resulting in slow and memory-intensive models. In this paper, we propose a
model based on the Hierarchical Recurrent Encoder Decoder (HRED) architecture.
This model independently encodes input sub-sequences without global context,
processes these sequences using a lower-frequency model, and decodes outputs at
the original data frequency. By interpreting the encoder as an implicitly
defined embedding matrix and using sampled softmax estimation, we develop a
training algorithm that can train the entire model without a high-frequency
decoder, which is the most memory and compute-intensive part of hierarchical
approaches. In a final, brief phase, we train the decoder to generate data at
the original granularity. Our algorithm significantly reduces memory
requirements for training autoregressive models and it also improves the total
training wall-clock time.