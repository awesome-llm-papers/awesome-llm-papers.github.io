---
layout: publication
title: Reformulating Unsupervised Style Transfer As Paraphrase Generation
authors: Krishna Kalpesh, Wieting John, Iyyer Mohit
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: krishna2020reformulating
citations: 175
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05700'}]
tags: [Training Techniques, EMNLP, Evaluation, Survey Paper, Reinforcement Learning,
  Fine Tuning, Datasets]
---
Modern NLP defines the task of style transfer as modifying the style of a
given sentence without appreciably changing its semantics, which implies that
the outputs of style transfer systems should be paraphrases of their inputs.
However, many existing systems purportedly designed for style transfer
inherently warp the input's meaning through attribute transfer, which changes
semantic properties such as sentiment. In this paper, we reformulate
unsupervised style transfer as a paraphrase generation problem, and present a
simple methodology based on fine-tuning pretrained language models on
automatically generated paraphrase data. Despite its simplicity, our method
significantly outperforms state-of-the-art style transfer systems on both human
and automatic evaluations. We also survey 23 style transfer papers and discover
that existing automatic metrics can be easily gamed and propose fixed variants.
Finally, we pivot to a more real-world style transfer setting by collecting a
large dataset of 15M sentences in 11 diverse styles, which we use for an
in-depth analysis of our system.