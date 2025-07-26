---
layout: publication
title: 'Delta Attention: Fast And Accurate Sparse Attention Inference By Delta Correction'
authors: Jeffrey Willette, Heejun Lee, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: willette2025delta
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.11254'}]
tags: ["Memory & Context", "Model Architecture"]
short_authors: Jeffrey Willette, Heejun Lee, Sung Ju Hwang
---
The attention mechanism of a transformer has a quadratic complexity, leading to high inference costs and latency for long sequences. However, attention matrices are mostly sparse, which implies that many entries may be omitted from computation for efficient inference. Sparse attention inference methods aim to reduce this computational burden; however, they also come with a troublesome performance degradation. We discover that one reason for this degradation is that the sparse calculation induces a distributional shift in the attention outputs. The distributional shift causes decoding-time queries to fail to align well with the appropriate keys from the prefill stage, leading to a drop in performance. We propose a simple, novel, and effective procedure for correcting this distributional shift, bringing the distribution of sparse attention outputs closer to that of quadratic attention. Our method can be applied on top of any sparse attention method, and results in an average 36%pt performance increase, recovering 88% of quadratic attention accuracy on the 131K RULER benchmark when applied on top of sliding window attention with sink tokens while only adding a small overhead. Our method can maintain approximately 98.5% sparsity over full quadratic attention, making our model 32 times faster than Flash Attention 2 when processing 1M token prefills.

https://huggingface.co/discussions/paper/682bf89aca2c97f999864e76