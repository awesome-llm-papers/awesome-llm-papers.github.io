---
layout: publication
title: Blending Complementary Memory Systems In Hybrid Quadratic-linear Transformers
authors: Irie Kazuki, Yau Morris, Gershman Samuel J.
conference: Proceedings of the 38th IEEE Conference on Decision and Control (Cat.
  No.99CH36304)
year: 2025
bibkey: irie2025blending
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00744'}]
tags: [RAG, Training Techniques, Attention Mechanism, Agentic, Transformer, Model
    Architecture, Language Modeling, Reinforcement Learning]
---
We develop hybrid memory architectures for general-purpose sequence processing neural networks, that combine key-value memory using softmax attention (KV-memory) with dynamic synaptic memory through fast-weight programming (FW-memory) -- the core principles of quadratic and linear transformers, respectively. These two memory systems have complementary but individually limited properties: KV-memory offers precise retrieval but is constrained by quadratic complexity in sequence length, while FW-memory supports arbitrarily long sequences and enables more expressive computation but sacrifices precise recall. We propose and compare three methods to blend these two systems into a single memory system to leverage the strengths of both. We conduct experiments on general language modeling and retrieval tasks by training 340M- and 1.3B-parameter models from scratch, as well as on synthetic algorithmic tasks designed to precisely illustrate the benefits of certain hybrid methods over others. We also evaluate our hybrid memory systems on reinforcement learning in partially observable environments. Overall, we demonstrate how a well-designed hybrid can overcome the limitations of its individual components, offering new insights into the design principle of neural memory systems.