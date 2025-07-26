---
layout: publication
title: Hurdles To Progress In Long-form Question Answering
authors: Kalpesh Krishna, Aurko Roy, Mohit Iyyer
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: krishna2021hurdles
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.06332'}]
tags: ["NAACL"]
short_authors: Kalpesh Krishna, Aurko Roy, Mohit Iyyer
---
The task of long-form question answering (LFQA) involves retrieving documents
relevant to a given question and using them to generate a paragraph-length
answer. While many models have recently been proposed for LFQA, we show in this
paper that the task formulation raises fundamental challenges regarding
evaluation and dataset creation that currently preclude meaningful modeling
progress. To demonstrate these challenges, we first design a new system that
relies on sparse attention and contrastive retriever learning to achieve
state-of-the-art performance on the ELI5 LFQA dataset. While our system tops
the public leaderboard, a detailed analysis reveals several troubling trends:
(1) our system's generated answers are not actually grounded in the documents
that it retrieves; (2) ELI5 contains significant train / validation overlap, as
at least 81% of ELI5 validation questions occur in paraphrased form in the
training set; (3) ROUGE-L is not an informative metric of generated answer
quality and can be easily gamed; and (4) human evaluations used for other text
generation tasks are unreliable for LFQA. We offer suggestions to mitigate each
of these issues, which we hope will lead to more rigorous LFQA research and
meaningful progress in the future.