---
layout: publication
title: 'Layoutlmv2: Multi-modal Pre-training For Visually-rich Document Understanding'
authors: Yang Xu, Yiheng Xu, Tengchao Lv, Lei Cui, Furu Wei, Guoxin Wang, Yijuan Lu,
  Dinei Florencio, Cha Zhang, Wanxiang Che, Min Zhang, Lidong Zhou
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: xu2020layoutlmv2
citations: 330
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.14740'}]
tags: ["Has Code", "Model Architecture", "Tools", "Training Techniques"]
short_authors: Xu et al.
---
Pre-training of text and layout has proved effective in a variety of
visually-rich document understanding tasks due to its effective model
architecture and the advantage of large-scale unlabeled scanned/digital-born
documents. We propose LayoutLMv2 architecture with new pre-training tasks to
model the interaction among text, layout, and image in a single multi-modal
framework. Specifically, with a two-stream multi-modal Transformer encoder,
LayoutLMv2 uses not only the existing masked visual-language modeling task but
also the new text-image alignment and text-image matching tasks, which make it
better capture the cross-modality interaction in the pre-training stage.
Meanwhile, it also integrates a spatial-aware self-attention mechanism into the
Transformer architecture so that the model can fully understand the relative
positional relationship among different text blocks. Experiment results show
that LayoutLMv2 outperforms LayoutLM by a large margin and achieves new
state-of-the-art results on a wide variety of downstream visually-rich document
understanding tasks, including FUNSD (0.7895 \\(\to\\) 0.8420), CORD (0.9493 \\(\to\\)
0.9601), SROIE (0.9524 \\(\to\\) 0.9781), Kleister-NDA (0.8340 \\(\to\\) 0.8520),
RVL-CDIP (0.9443 \\(\to\\) 0.9564), and DocVQA (0.7295 \\(\to\\) 0.8672). We made our
model and code publicly available at https://aka.ms/layoutlmv2.