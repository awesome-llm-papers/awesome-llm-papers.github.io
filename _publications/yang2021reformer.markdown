---
layout: publication
title: 'Reformer: The Relational Transformer For Image Captioning'
authors: Yang Xuewen, Liu Yingru, Wang Xin
conference: Proceedings of the 30th ACM International Conference on Multimedia
year: 2021
bibkey: yang2021reformer
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.14178'}]
tags: [Interpretability And Explainability, Model Architecture, Datasets, Transformer]
---
Image captioning is shown to be able to achieve a better performance by using
scene graphs to represent the relations of objects in the image. The current
captioning encoders generally use a Graph Convolutional Net (GCN) to represent
the relation information and merge it with the object region features via
concatenation or convolution to get the final input for sentence decoding.
However, the GCN-based encoders in the existing methods are less effective for
captioning due to two reasons. First, using the image captioning as the
objective (i.e., Maximum Likelihood Estimation) rather than a relation-centric
loss cannot fully explore the potential of the encoder. Second, using a
pre-trained model instead of the encoder itself to extract the relationships is
not flexible and cannot contribute to the explainability of the model. To
improve the quality of image captioning, we propose a novel architecture
ReFormer -- a RElational transFORMER to generate features with relation
information embedded and to explicitly express the pair-wise relationships
between objects in the image. ReFormer incorporates the objective of scene
graph generation with that of image captioning using one modified Transformer
model. This design allows ReFormer to generate not only better image captions
with the bene-fit of extracting strong relational image features, but also
scene graphs to explicitly describe the pair-wise relation-ships. Experiments
on publicly available datasets show that our model significantly outperforms
state-of-the-art methods on image captioning and scene graph generation