---
layout: publication
title: 'Beyond Scaling Laws: Understanding Transformer Performance With Associative
  Memory'
authors: Xueyan Niu, Bo Bai, Lei Deng, Wei Han
conference: No Venue
year: 2024
bibkey: niu2024beyond
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2405.08707'}]
tags: ["Model Architecture"]
short_authors: Niu et al.
---
Increasing the size of a Transformer model does not always lead to enhanced performance. This phenomenon cannot be explained by the empirical scaling laws. Furthermore, improved generalization ability occurs as the model memorizes the training samples. We present a theoretical framework that sheds light on the memorization process and performance dynamics of transformer-based language models. We model the behavior of Transformers with associative memories using Hopfield networks, such that each transformer block effectively conducts an approximate nearest-neighbor search. Based on this, we design an energy function analogous to that in the modern continuous Hopfield network which provides an insightful explanation for the attention mechanism. Using the majorization-minimization technique, we construct a global energy function that captures the layered architecture of the Transformer. Under specific conditions, we show that the minimum achievable cross-entropy loss is bounded from below by a constant approximately equal to 1. We substantiate our theoretical results by conducting experiments with GPT-2 on various data sizes, as well as training vanilla Transformers on a dataset of 2M tokens.

https://huggingface.co/discussions/paper/6644fb26c1a4481c95a34c42