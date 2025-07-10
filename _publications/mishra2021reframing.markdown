---
layout: publication
title: Reframing Instructional Prompts To Gptk's Language
authors: Swaroop Mishra, Daniel Khashabi, Chitta Baral, Yejin Choi, Hannaneh Hajishirzi
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2021
citations: 29
bibkey: mishra2021reframing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.07830'}]
tags: [Model Architecture, Few-Shot, RAG, Prompting, GPT]
---
What kinds of instructional prompts are easier to follow for Language Models
(LMs)? We study this question by conducting extensive empirical analysis that
shed light on important features of successful instructional prompts.
Specifically, we study several classes of reframing techniques for manual
reformulation of prompts into more effective ones. Some examples include
decomposing a complex task instruction into multiple simpler tasks or itemizing
instructions into sequential steps. Our experiments compare the zero-shot and
few-shot performance of LMs prompted with reframed instructions on 12 NLP tasks
across 6 categories. Compared with original instructions, our reframed
instructions lead to significant improvements across LMs with different sizes.
For example, the same reframed prompts boost few-shot performance of
GPT3-series and GPT2-series by 12.5% and 6.7% respectively averaged over all
tasks. Furthermore, reframed instructions reduce the number of examples
required to prompt LMs in the few-shot setting. We hope these
empirically-driven techniques will pave the way towards more effective future
prompting algorithms.