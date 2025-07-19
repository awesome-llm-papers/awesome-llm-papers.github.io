---
layout: publication
title: Towards Unsupervised Image Captioning With Shared Multimodal Embeddings
authors: Laina Iro, Rupprecht Christian, Navab Nassir
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: laina2019towards
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.09317'}]
tags: [Multimodal Models, Reinforcement Learning, Security, ICCV]
---
Understanding images without explicit supervision has become an important
problem in computer vision. In this paper, we address image captioning by
generating language descriptions of scenes without learning from annotated
pairs of images and their captions. The core component of our approach is a
shared latent space that is structured by visual concepts. In this space, the
two modalities should be indistinguishable. A language model is first trained
to encode sentences into semantically structured embeddings. Image features
that are translated into this embedding space can be decoded into descriptions
through the same language model, similarly to sentence embeddings. This
translation is learned from weakly paired images and text using a loss robust
to noisy assignments and a conditional adversarial component. Our approach
allows to exploit large text corpora outside the annotated distributions of
image/caption data. Our experiments show that the proposed domain alignment
learns a semantically meaningful representation which outperforms previous
work.