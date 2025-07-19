---
layout: publication
title: How Sparse Attention Approximates Exact Attention? Your Attention Is Naturally
  \(n^c\)-sparse
authors: Deng et al.
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2024
bibkey: deng2024how
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.02690'}]
tags: [Attention Mechanism, Tools, Transformer, Model Architecture, Efficiency And
    Optimization, Pruning]
---
Sparse Attention is a technique that approximates standard attention
computation with sub-quadratic complexity. This is achieved by selectively
ignoring smaller entries in the attention matrix during the softmax function
computation. Variations of this technique, such as pruning KV cache,
sparsity-based fast attention, and Sparse Transformer, have been extensively
utilized for efficient Large Language Models (LLMs) deployment. Despite its
widespread use, a theoretical understanding of the conditions under which
sparse attention performs on par with traditional attention remains elusive.
This work aims to \\(\textbf\{bridge this gap by examining the inherent sparsity
of standard attention processes\}\\). Our theoretical framework reveals several
brand-new key insights:
  \\(\bullet\\) Attention is \\(n^\{C\}\\)-sparse, implying that considering only the
largest \\(Ω(n^\{C\})\\) entries out of all \\(n\\) entries is sufficient for sparse
attention to approximate the exact attention matrix with decreasing loss. Here,
\\(n\\) represents the input length and \\(C \in (0, 1)\\) is a constant.
  \\(\bullet\\) Stable \\(o(log(n))\\)-sparse attention, which approximates attention
computation with \\(log(n)\\) or fewer entries, may not be feasible since the
error will persist at a minimum of \\(O(1)\\).
  \\(\bullet\\) An adaptive strategy (\\(\alpha \cdot n^C, \alpha \in \mathbb\{R\}\\))
for the window size of efficient attention methods rather than a fixed one is
guaranteed to perform more accurately and efficiently in a task for inference
on flexible context lengths.