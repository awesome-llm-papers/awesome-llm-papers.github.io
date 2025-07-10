---
layout: publication
title: 'Hungry Hungry Hippos: Towards Language Modeling With State Space Models'
authors: Daniel Y. Fu et al.
conference: Arxiv
year: 2022
citations: 39
bibkey: fu2022hungry
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.14052'}]
tags: [Language Modeling, Model Architecture, Attention Mechanism, Transformer, Few-Shot,
  Tools, Reinforcement Learning, Efficiency and Optimization, Training Techniques,
  Evaluation]
---
State space models (SSMs) have demonstrated state-of-the-art sequence
modeling performance in some modalities, but underperform attention in language
modeling. Moreover, despite scaling nearly linearly in sequence length instead
of quadratically, SSMs are still slower than Transformers due to poor hardware
utilization. In this paper, we make progress on understanding the expressivity
gap between SSMs and attention in language modeling, and on reducing the
hardware barrier between SSMs and attention. First, we use synthetic language
modeling tasks to understand the gap between SSMs and attention. We find that
existing SSMs struggle with two capabilities: recalling earlier tokens in the
sequence and comparing tokens across the sequence. To understand the impact on
language modeling, we propose a new SSM layer, H3, that is explicitly designed
for these abilities. H3 matches attention on the synthetic languages and comes
within 0.4 PPL of Transformers on OpenWebText. Furthermore, a hybrid
125M-parameter H3-attention model that retains two attention layers
surprisingly outperforms Transformers on OpenWebText by 1.0 PPL. Next, to
improve the efficiency of training SSMs on modern hardware, we propose
FlashConv. FlashConv uses a fused block FFT algorithm to improve efficiency on
sequences up to 8K, and introduces a novel state passing algorithm that
exploits the recurrent properties of SSMs to scale to longer sequences.
FlashConv yields 2\\(\times\\) speedup on the long-range arena benchmark and allows
hybrid language models to generate text 2.4\\(\times\\) faster than Transformers.
Using FlashConv, we scale hybrid H3-attention language models up to 2.7B
parameters on the Pile and find promising initial results, achieving lower
perplexity than Transformers and outperforming Transformers in zero- and
few-shot learning on a majority of tasks in the SuperGLUE benchmark.