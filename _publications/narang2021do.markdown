---
layout: publication
title: Do Transformer Modifications Transfer Across Implementations And Applications?
authors: Sharan Narang, Hyung Won Chung, Yi Tay, William Fedus, Thibault Fevry, Michael
  Matena, Karishma Malkan, Noah Fiedel, Noam Shazeer, Zhenzhong Lan, Yanqi Zhou, Wei
  Li, Nan Ding, Jake Marcus, Adam Roberts, Colin Raffel
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: narang2021do
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.11972'}]
tags: ["Applications", "EMNLP", "Model Architecture"]
short_authors: Narang et al.
---
The research community has proposed copious modifications to the Transformer
architecture since it was introduced over three years ago, relatively few of
which have seen widespread adoption. In this paper, we comprehensively evaluate
many of these modifications in a shared experimental setting that covers most
of the common uses of the Transformer in natural language processing.
Surprisingly, we find that most modifications do not meaningfully improve
performance. Furthermore, most of the Transformer variants we found beneficial
were either developed in the same codebase that we used or are relatively minor
changes. We conjecture that performance improvements may strongly depend on
implementation details and correspondingly make some recommendations for
improving the generality of experimental results.