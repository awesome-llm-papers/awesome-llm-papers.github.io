---
layout: publication
title: Geometry Attention Transformer With Position-aware Lstms For Image Captioning
authors: Wang Chi, Shen Yulin, Ji Luping
conference: Expert Systems with Applications
year: 2021
bibkey: wang2021geometry
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.00335'}]
tags: [RAG, Attention Mechanism, Transformer, Model Architecture, Applications, Datasets]
---
In recent years, transformer structures have been widely applied in image
captioning with impressive performance. For good captioning results, the
geometry and position relations of different visual objects are often thought
of as crucial information. Aiming to further promote image captioning by
transformers, this paper proposes an improved Geometry Attention Transformer
(GAT) model. In order to further leverage geometric information, two novel
geometry-aware architectures are designed respectively for the encoder and
decoder in our GAT. Besides, this model includes the two work modules: 1) a
geometry gate-controlled self-attention refiner, for explicitly incorporating
relative spatial information into image region representations in encoding
steps, and 2) a group of position-LSTMs, for precisely informing the decoder of
relative word position in generating caption texts. The experiment comparisons
on the datasets MS COCO and Flickr30K show that our GAT is efficient, and it
could often outperform current state-of-the-art image captioning models.