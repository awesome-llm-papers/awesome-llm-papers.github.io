---
layout: publication
title: 'Gptscore: Evaluate As You Desire'
authors: Jinlan Fu, See-kiong Ng, Zhengbao Jiang, Pengfei Liu
conference: Arxiv
year: 2023
bibkey: fu2023gptscore
citations: 74
additional_links: [{name: Code, url: 'https://github.com/jinlanfu/GPTScore'}, {name: Paper,
    url: 'https://arxiv.org/abs/2302.04166'}]
tags: ["Evaluation", "Has Code", "Tools"]
short_authors: Fu et al.
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