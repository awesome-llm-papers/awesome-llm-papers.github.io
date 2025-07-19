---
layout: publication
title: 'CPTR: Full Transformer Network For Image Captioning'
authors: Liu et al.
conference: Arxiv
year: 2021
bibkey: liu2021cptr
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.10804'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Language Modeling, Datasets]
---
In this paper, we consider the image captioning task from a new
sequence-to-sequence prediction perspective and propose CaPtion TransformeR
(CPTR) which takes the sequentialized raw images as the input to Transformer.
Compared to the "CNN+Transformer" design paradigm, our model can model global
context at every encoder layer from the beginning and is totally
convolution-free. Extensive experiments demonstrate the effectiveness of the
proposed model and we surpass the conventional "CNN+Transformer" methods on the
MSCOCO dataset. Besides, we provide detailed visualizations of the
self-attention between patches in the encoder and the "words-to-patches"
attention in the decoder thanks to the full Transformer architecture.