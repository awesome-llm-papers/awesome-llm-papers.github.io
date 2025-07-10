---
layout: publication
title: 'Self-adaptive In-context Learning: An Information Compression Perspective
  For In-context Example Selection And Ordering'
authors: Zhiyong Wu, Yaoxiang Wang, Jiacheng Ye, Lingpeng Kong
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
citations: 24
bibkey: wu2022self
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2212.10375v2'}, {name: Code,
    url: 'https://github.com/Shark-NLP/self-adaptive-ICL'}]
tags: [Has Code, Few-Shot, Tools, In-Context Learning, Evaluation]
---
Despite the surprising few-shot performance of in-context learning (ICL), it
is still a common practice to randomly sample examples to serve as context.
This paper advocates a new principle for ICL: self-adaptive in-context
learning. The self-adaption mechanism is introduced to help each sample find an
in-context example permutation (i.e., selection and ordering) that can derive
the correct prediction, thus maximizing performance. To validate the
effectiveness of self-adaptive ICL, we propose a general select-then-rank
framework and instantiate it with new selection and ranking algorithms. Upon
extensive evaluation on eight different NLP datasets, our self-adaptive ICL
method achieves a 40% relative improvement over the common practice setting.
Further analysis reveals the enormous potential of self-adaptive ICL that it
might be able to close the gap between ICL and finetuning given more advanced
algorithms. Our code is released to facilitate future research in this area:
https://github.com/Shark-NLP/self-adaptive-ICL