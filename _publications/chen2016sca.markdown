---
layout: publication
title: 'SCA-CNN: Spatial And Channel-wise Attention In Convolutional Networks For
  Image Captioning'
authors: Long Chen, Hanwang Zhang, Jun Xiao, Liqiang Nie, Jian Shao, Wei Liu, Tat-seng
  Chua
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2017
bibkey: chen2016sca
citations: 1911
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.05594'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Chen et al.
---
Visual attention has been successfully applied in structural prediction tasks
such as visual captioning and question answering. Existing visual attention
models are generally spatial, i.e., the attention is modeled as spatial
probabilities that re-weight the last conv-layer feature map of a CNN encoding
an input image. However, we argue that such spatial attention does not
necessarily conform to the attention mechanism --- a dynamic feature extractor
that combines contextual fixations over time, as CNN features are naturally
spatial, channel-wise and multi-layer. In this paper, we introduce a novel
convolutional neural network dubbed SCA-CNN that incorporates Spatial and
Channel-wise Attentions in a CNN. In the task of image captioning, SCA-CNN
dynamically modulates the sentence generation context in multi-layer feature
maps, encoding where (i.e., attentive spatial locations at multiple layers) and
what (i.e., attentive channels) the visual attention is. We evaluate the
proposed SCA-CNN architecture on three benchmark image captioning datasets:
Flickr8K, Flickr30K, and MSCOCO. It is consistently observed that SCA-CNN
significantly outperforms state-of-the-art visual attention-based image
captioning methods.