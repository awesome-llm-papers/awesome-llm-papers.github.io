---
layout: publication
title: 'Gptscore: Evaluate As You Desire'
authors: Jinlan Fu, See-kiong Ng, Zhengbao Jiang, Pengfei Liu
conference: 'Proceedings of the 2024 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies (Volume 1:
  Long Papers)'
year: 2023
citations: 56
bibkey: fu2023evaluate
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.04166'}, {name: Code,
    url: 'https://github.com/jinlanfu/GPTScore'}]
tags: [Has Code, Model Architecture, Tools, GPT, Evaluation]
---
Generative Artificial Intelligence (AI) has enabled the development of
sophisticated models that are capable of producing high-caliber text, images,
and other outputs through the utilization of large pre-trained models.
Nevertheless, assessing the quality of the generation is an even more arduous
task than the generation itself, and this issue has not been given adequate
consideration recently. This paper proposes a novel evaluation framework,
GPTScore, which utilizes the emergent abilities (e.g., zero-shot instruction)
of generative pre-trained models to score generated texts. There are 19
pre-trained models explored in this paper, ranging in size from 80M (e.g.,
FLAN-T5-small) to 175B (e.g., GPT3). Experimental results on four text
generation tasks, 22 evaluation aspects, and corresponding 37 datasets
demonstrate that this approach can effectively allow us to achieve what one
desires to evaluate for texts simply by natural language instructions. This
nature helps us overcome several long-standing challenges in text
evaluation--how to achieve customized, multi-faceted evaluation without the
need for annotated samples. We make our code publicly available at
https://github.com/jinlanfu/GPTScore.