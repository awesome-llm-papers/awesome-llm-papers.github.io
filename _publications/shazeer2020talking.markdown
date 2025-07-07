---
layout: publication
title: Talking-heads Attention
authors: Noam Shazeer, Zhenzhong Lan, Youlong Cheng, Nan Ding, Le Hou
conference: Arxiv
year: 2020
citations: 49
bibkey: shazeer2020talking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.02436'}]
tags: [Attention Mechanism, Model Architecture]
---
We introduce "talking-heads attention" - a variation on multi-head attention
which includes linearprojections across the attention-heads dimension,
immediately before and after the softmax operation.While inserting only a small
number of additional parameters and a moderate amount of additionalcomputation,
talking-heads attention leads to better perplexities on masked language
modeling tasks, aswell as better quality when transfer-learning to language
comprehension and question answering tasks.