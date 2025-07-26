---
layout: publication
title: 'Scaling Up Test-time Compute With Latent Reasoning: A Recurrent Depth Approach'
authors: Jonas Geiping, Sean Mcleish, Neel Jain, John Kirchenbauer, Siddharth Singh,
  Brian R. Bartoldson, Bhavya Kailkhura, Abhinav Bhatele, Tom Goldstein
conference: No Venue
year: 2025
bibkey: geiping2025scaling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.05171'}]
tags: ["Model Architecture"]
short_authors: Geiping et al.
---
We study a novel language model architecture that is capable of scaling test-time computation by implicitly reasoning in latent space. Our model works by iterating a recurrent block, thereby unrolling to arbitrary depth at test-time. This stands in contrast to mainstream reasoning models that scale up compute by producing more tokens. Unlike approaches based on chain-of-thought, our approach does not require any specialized training data, can work with small context windows, and can capture types of reasoning that are not easily represented in words. We scale a proof-of-concept model to 3.5 billion parameters and 800 billion tokens. We show that the resulting model can improve its performance on reasoning benchmarks, sometimes dramatically, up to a computation load equivalent to 50 billion parameters.

https://huggingface.co/discussions/paper/67a97e29495b23306cd5eae5