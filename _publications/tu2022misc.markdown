---
layout: publication
title: 'MISC: A Mixed Strategy-aware Model Integrating COMET For Emotional Support
  Conversation'
authors: Tu et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: tu2022misc
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.13560'}]
tags: [Datasets, Reinforcement Learning, ACL, Evaluation]
---
Applying existing methods to emotional support conversation -- which provides
valuable assistance to people who are in need -- has two major limitations: (a)
they generally employ a conversation-level emotion label, which is too
coarse-grained to capture user's instant mental state; (b) most of them focus
on expressing empathy in the response(s) rather than gradually reducing user's
distress. To address the problems, we propose a novel model \textbf\{MISC\},
which firstly infers the user's fine-grained emotional status, and then
responds skillfully using a mixture of strategy. Experimental results on the
benchmark dataset demonstrate the effectiveness of our method and reveal the
benefits of fine-grained emotion understanding as well as mixed-up strategy
modeling. Our code and data could be found in
https://github.com/morecry/MISC.