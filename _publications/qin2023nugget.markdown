---
layout: publication
title: 'Nugget: Neural Agglomerative Embeddings Of Text'
authors: Qin Guanghui, van Durme Benjamin
conference: Proceedings of the Tenth ACM International Conference on Web Search and
  Data Mining
year: 2023
bibkey: qin2023nugget
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.01732'}]
tags: []
---
Embedding text sequences is a widespread requirement in modern language
understanding. Existing approaches focus largely on constant-size
representations. This is problematic, as the amount of information contained in
text often varies with the length of the input. We propose a solution called
Nugget, which encodes language into a representation based on a dynamically
selected subset of input tokens. These nuggets are learned through tasks like
autoencoding and machine translation, and intuitively segment language into
meaningful units. We demonstrate Nugget outperforms related approaches in tasks
involving semantic comparison. Finally, we illustrate these compact units allow
for expanding the contextual window of a language model (LM), suggesting new
future LMs that can condition on significantly larger amounts of content.