---
layout: publication
title: Semantically Conditioned Dialog Response Generation Via Hierarchical Disentangled
  Self-attention
authors: Wenhu Chen, Jianshu Chen, Pengda Qin, Xifeng Yan, William Yang Wang
conference: Arxiv
year: 2019
citations: 38
bibkey: chen2019semantically
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.12866'}]
tags: [Ethics and Bias, Attention Mechanism, Transformer, Model Architecture]
---
Semantically controlled neural response generation on limited-domain has
achieved great performance. However, moving towards multi-domain large-scale
scenarios are shown to be difficult because the possible combinations of
semantic inputs grow exponentially with the number of domains. To alleviate
such scalability issue, we exploit the structure of dialog acts to build a
multi-layer hierarchical graph, where each act is represented as a root-to-leaf
route on the graph. Then, we incorporate such graph structure prior as an
inductive bias to build a hierarchical disentangled self-attention network,
where we disentangle attention heads to model designated nodes on the dialog
act graph. By activating different (disentangled) heads at each layer,
combinatorially many dialog act semantics can be modeled to control the neural
response generation. On the large-scale Multi-Domain-WOZ dataset, our model can
yield a significant improvement over the baselines on various automatic and
human evaluation metrics.