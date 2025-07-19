---
layout: publication
title: 'Lost In The Middle: How Language Models Use Long Contexts'
authors: Liu et al.
conference: Transactions of the Association for Computational Linguistics
year: 2023
bibkey: liu2023lost
citations: 234
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.03172'}]
tags: [TACL, ACL, Evaluation]
---
While recent language models have the ability to take long contexts as input,
relatively little is known about how well they use longer context. We analyze
the performance of language models on two tasks that require identifying
relevant information in their input contexts: multi-document question answering
and key-value retrieval. We find that performance can degrade significantly
when changing the position of relevant information, indicating that current
language models do not robustly make use of information in long input contexts.
In particular, we observe that performance is often highest when relevant
information occurs at the beginning or end of the input context, and
significantly degrades when models must access relevant information in the
middle of long contexts, even for explicitly long-context models. Our analysis
provides a better understanding of how language models use their input context
and provides new evaluation protocols for future long-context language models.