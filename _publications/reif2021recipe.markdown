---
layout: publication
title: A Recipe For Arbitrary Text Style Transfer With Large Language Models
authors: Emily Reif et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2021
citations: 28
bibkey: reif2021recipe
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.03910'}]
tags: [Training Techniques, Fine-Tuning, Prompting, RAG]
---
In this paper, we leverage large language models (LMs) to perform zero-shot
text style transfer. We present a prompting method that we call augmented
zero-shot learning, which frames style transfer as a sentence rewriting task
and requires only a natural language instruction, without model fine-tuning or
exemplars in the target style. Augmented zero-shot learning is simple and
demonstrates promising results not just on standard style transfer tasks such
as sentiment, but also on arbitrary transformations such as "make this
melodramatic" or "insert a metaphor."