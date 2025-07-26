---
layout: publication
title: Continuous-time Sequential Recommendation With Temporal Graph Collaborative
  Transformer
authors: Ziwei Fan, Zhiwei Liu, Jiawei Zhang, Yun Xiong, Lei Zheng, Philip S. Yu
conference: Proceedings of the 30th ACM International Conference on Information &amp;
  Knowledge Management
year: 2021
bibkey: fan2021continuous
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.06625'}]
tags: ["CIKM", "Model Architecture"]
short_authors: Fan et al.
---
In order to model the evolution of user preference, we should learn user/item
embeddings based on time-ordered item purchasing sequences, which is defined as
Sequential Recommendation (SR) problem. Existing methods leverage sequential
patterns to model item transitions. However, most of them ignore crucial
temporal collaborative signals, which are latent in evolving user-item
interactions and coexist with sequential patterns. Therefore, we propose to
unify sequential patterns and temporal collaborative signals to improve the
quality of recommendation, which is rather challenging. Firstly, it is hard to
simultaneously encode sequential patterns and collaborative signals. Secondly,
it is non-trivial to express the temporal effects of collaborative signals.
  Hence, we design a new framework Temporal Graph Sequential Recommender
(TGSRec) upon our defined continuous-time bi-partite graph. We propose a novel
Temporal Collaborative Trans-former (TCT) layer in TGSRec, which advances the
self-attention mechanism by adopting a novel collaborative attention. TCT layer
can simultaneously capture collaborative signals from both users and items, as
well as considering temporal dynamics inside sequential patterns. We propagate
the information learned fromTCTlayerover the temporal graph to unify sequential
patterns and temporal collaborative signals. Empirical results on five datasets
show that TGSRec significantly outperforms other baselines, in average up to
22.5% and 22.1%absolute improvements in Recall@10and MRR, respectively.