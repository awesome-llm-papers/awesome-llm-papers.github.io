---
layout: publication
title: Non-invasive Self-attention For Side Information Fusion In Sequential Recommendation
authors: Liu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: liu2021non
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.03578'}]
tags: [RAG, Attention Mechanism, Alt, Tools, Transformer, BERT, Model Architecture,
  AAAI, Datasets, Merging]
---
Sequential recommender systems aim to model users' evolving interests from
their historical behaviors, and hence make customized time-relevant
recommendations. Compared with traditional models, deep learning approaches
such as CNN and RNN have achieved remarkable advancements in recommendation
tasks. Recently, the BERT framework also emerges as a promising method,
benefited from its self-attention mechanism in processing sequential data.
However, one limitation of the original BERT framework is that it only
considers one input source of the natural language tokens. It is still an open
question to leverage various types of information under the BERT framework.
Nonetheless, it is intuitively appealing to utilize other side information,
such as item category or tag, for more comprehensive depictions and better
recommendations. In our pilot experiments, we found naive approaches, which
directly fuse types of side information into the item embeddings, usually bring
very little or even negative effects. Therefore, in this paper, we propose the
NOninVasive self-attention mechanism (NOVA) to leverage side information
effectively under the BERT framework. NOVA makes use of side information to
generate better attention distribution, rather than directly altering the item
embedding, which may cause information overwhelming. We validate the NOVA-BERT
model on both public and commercial datasets, and our method can stably
outperform the state-of-the-art models with negligible computational overheads.