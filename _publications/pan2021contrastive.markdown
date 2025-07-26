---
layout: publication
title: Contrastive Learning For Many-to-many Multilingual Neural Machine Translation
authors: Xiao Pan, Mingxuan Wang, Liwei Wu, Lei Li
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: pan2021contrastive
citations: 120
additional_links: [{name: Code, url: 'https://github.com/PANXiao1994/mRASP2'}, {name: Paper,
    url: 'https://arxiv.org/abs/2105.09501'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Pan et al.
---
Existing multilingual machine translation approaches mainly focus on
English-centric directions, while the non-English directions still lag behind.
In this work, we aim to build a many-to-many translation system with an
emphasis on the quality of non-English language directions. Our intuition is
based on the hypothesis that a universal cross-language representation leads to
better multilingual translation performance. To this end, we propose mRASP2, a
training method to obtain a single unified multilingual translation model.
mRASP2 is empowered by two techniques: a) a contrastive learning scheme to
close the gap among representations of different languages, and b) data
augmentation on both multiple parallel and monolingual data to further align
token representations. For English-centric directions, mRASP2 outperforms
existing best unified model and achieves competitive or even better performance
than the pre-trained and fine-tuned model mBART on tens of WMT's translation
directions. For non-English directions, mRASP2 achieves an improvement of
average 10+ BLEU compared with the multilingual Transformer baseline. Code,
data and trained models are available at https://github.com/PANXiao1994/mRASP2.