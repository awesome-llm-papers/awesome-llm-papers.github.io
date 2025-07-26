---
layout: publication
title: Understanding And Improving Encoder Layer Fusion In Sequence-to-sequence Learning
authors: Xuebo Liu, Longyue Wang, Derek F. Wong, Liang Ding, Lidia S. Chao, Zhaopeng
  Tu
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: liu2020understanding
citations: 140
additional_links: [{name: Code, url: 'https://github.com/SunbowLiu/SurfaceFusion'},
  {name: Paper, url: 'https://arxiv.org/abs/2012.14768'}]
tags: ["EMNLP"]
short_authors: Liu et al.
---
Encoder layer fusion (EncoderFusion) is a technique to fuse all the encoder
layers (instead of the uppermost layer) for sequence-to-sequence (Seq2Seq)
models, which has proven effective on various NLP tasks. However, it is still
not entirely clear why and when EncoderFusion should work. In this paper, our
main contribution is to take a step further in understanding EncoderFusion.
Many of previous studies believe that the success of EncoderFusion comes from
exploiting surface and syntactic information embedded in lower encoder layers.
Unlike them, we find that the encoder embedding layer is more important than
other intermediate encoder layers. In addition, the uppermost decoder layer
consistently pays more attention to the encoder embedding layer across NLP
tasks. Based on this observation, we propose a simple fusion method,
SurfaceFusion, by fusing only the encoder embedding layer for the softmax
layer. Experimental results show that SurfaceFusion outperforms EncoderFusion
on several NLP benchmarks, including machine translation, text summarization,
and grammatical error correction. It obtains the state-of-the-art performance
on WMT16 Romanian-English and WMT14 English-French translation tasks. Extensive
analyses reveal that SurfaceFusion learns more expressive bilingual word
embeddings by building a closer relationship between relevant source and target
embedding. Source code is freely available at
https://github.com/SunbowLiu/SurfaceFusion.