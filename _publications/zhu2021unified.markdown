---
layout: publication
title: A Unified Framework For Cross-domain And Cross-system Recommendations
authors: Zhu et al.
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2021
bibkey: zhu2021unified
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.07976'}]
tags: [Training Techniques, Attention Mechanism, Tools, Transformer, Model Architecture,
  Reinforcement Learning, Datasets]
---
Cross-Domain Recommendation (CDR) and Cross-System Recommendation (CSR) have
been proposed to improve the recommendation accuracy in a target dataset
(domain/system) with the help of a source one with relatively richer
information. However, most existing CDR and CSR approaches are single-target,
namely, there is a single target dataset, which can only help the target
dataset and thus cannot benefit the source dataset. In this paper, we focus on
three new scenarios, i.e., Dual-Target CDR (DTCDR), Multi-Target CDR (MTCDR),
and CDR+CSR, and aim to improve the recommendation accuracy in all datasets
simultaneously for all scenarios. To do this, we propose a unified framework,
called GA (based on Graph embedding and Attention techniques), for all three
scenarios. In GA, we first construct separate heterogeneous graphs to generate
more representative user and item embeddings. Then, we propose an element-wise
attention mechanism to effectively combine the embeddings of common entities
(users/items) learned from different datasets. Moreover, to avoid negative
transfer, we further propose a Personalized training strategy to minimize the
embedding difference of common entities between a richer dataset and a sparser
dataset, deriving three new models, i.e., GA-DTCDR-P, GA-MTCDR-P, and
GA-CDR+CSR-P, for the three scenarios respectively. Extensive experiments
conducted on four real-world datasets demonstrate that our proposed GA models
significantly outperform the state-of-the-art approaches.