---
layout: publication
title: Improving Image Captioning By Leveraging Intra- And Inter-layer Global Representation
  In Transformer Network
authors: Jiayi Ji, Yunpeng Luo, Xiaoshuai Sun, Fuhai Chen, Gen Luo, Yongjian Wu, Yue
  Gao, Rongrong Ji
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: ji2020improving
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.07061'}]
tags: ["AAAI", "Datasets", "Model Architecture"]
short_authors: Ji et al.
---
Transformer-based architectures have shown great success in image captioning,
where object regions are encoded and then attended into the vectorial
representations to guide the caption decoding. However, such vectorial
representations only contain region-level information without considering the
global information reflecting the entire image, which fails to expand the
capability of complex multi-modal reasoning in image captioning. In this paper,
we introduce a Global Enhanced Transformer (termed GET) to enable the
extraction of a more comprehensive global representation, and then adaptively
guide the decoder to generate high-quality captions. In GET, a Global Enhanced
Encoder is designed for the embedding of the global feature, and a Global
Adaptive Decoder are designed for the guidance of the caption generation. The
former models intra- and inter-layer global representation by taking advantage
of the proposed Global Enhanced Attention and a layer-wise fusion module. The
latter contains a Global Adaptive Controller that can adaptively fuse the
global information into the decoder to guide the caption generation. Extensive
experiments on MS COCO dataset demonstrate the superiority of our GET over many
state-of-the-arts.