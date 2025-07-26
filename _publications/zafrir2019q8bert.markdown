---
layout: publication
title: 'Q8BERT: Quantized 8bit BERT'
authors: Ofir Zafrir, Guy Boudoukh, Peter Izsak, Moshe Wasserblat
conference: 2019 Fifth Workshop on Energy Efficient Machine Learning and Cognitive
  Computing - NeurIPS Edition (EMC2-NIPS)
year: 2019
bibkey: zafrir2019q8bert
citations: 378
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.06188'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Zafrir et al.
---
Recently, pre-trained Transformer based language models such as BERT and GPT,
have shown great improvement in many Natural Language Processing (NLP) tasks.
However, these models contain a large amount of parameters. The emergence of
even larger and more accurate models such as GPT2 and Megatron, suggest a trend
of large pre-trained Transformer models. However, using these large models in
production environments is a complex task requiring a large amount of compute,
memory and power resources. In this work we show how to perform
quantization-aware training during the fine-tuning phase of BERT in order to
compress BERT by \\(4\times\\) with minimal accuracy loss. Furthermore, the
produced quantized model can accelerate inference speed if it is optimized for
8bit Integer supporting hardware.