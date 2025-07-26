---
layout: publication
title: 'Linformer: Self-attention With Linear Complexity'
authors: Sinong Wang, Belinda Z. Li, Madian Khabsa, Han Fang, Hao Ma
conference: Arxiv
year: 2020
bibkey: wang2020linformer
citations: 856
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.04768'}]
tags: ["Model Architecture"]
short_authors: Wang et al.
---
Large transformer models have shown extraordinary success in achieving
state-of-the-art results in many natural language processing applications.
However, training and deploying these models can be prohibitively costly for
long sequences, as the standard self-attention mechanism of the Transformer
uses \\(O(n^2)\\) time and space with respect to sequence length. In this paper, we
demonstrate that the self-attention mechanism can be approximated by a low-rank
matrix. We further exploit this finding to propose a new self-attention
mechanism, which reduces the overall self-attention complexity from \\(O(n^2)\\) to
\\(O(n)\\) in both time and space. The resulting linear transformer, the
\textit\{Linformer\}, performs on par with standard Transformer models, while
being much more memory- and time-efficient.