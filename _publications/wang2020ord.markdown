---
layout: publication
title: 'ORD: Object Relationship Discovery For Visual Dialogue Generation'
authors: Wang et al.
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: wang2020ord
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.08322'}]
tags: [Attention Mechanism, Tools, CVPR, Transformer, Model Architecture, Datasets]
---
With the rapid advancement of image captioning and visual question answering
at single-round level, the question of how to generate multi-round dialogue
about visual content has not yet been well explored.Existing visual dialogue
methods encode the image into a fixed feature vector directly, concatenated
with the question and history embeddings to predict the response.Some recent
methods tackle the co-reference resolution problem using co-attention mechanism
to cross-refer relevant elements from the image, history, and the target
question.However, it remains challenging to reason visual relationships, since
the fine-grained object-level information is omitted before co-attentive
reasoning. In this paper, we propose an object relationship discovery (ORD)
framework to preserve the object interactions for visual dialogue generation.
Specifically, a hierarchical graph convolutional network (HierGCN) is proposed
to retain the object nodes and neighbour relationships locally, and then
refines the object-object connections globally to obtain the final graph
embeddings. A graph attention is further incorporated to dynamically attend to
this graph-structured representation at the response reasoning stage. Extensive
experiments have proved that the proposed method can significantly improve the
quality of dialogue by utilising the contextual information of visual
relationships. The model achieves superior performance over the
state-of-the-art methods on the Visual Dialog dataset, increasing MRR from
0.6222 to 0.6447, and recall@1 from 48.48% to 51.22%.