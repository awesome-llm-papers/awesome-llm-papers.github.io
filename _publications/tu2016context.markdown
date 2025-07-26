---
layout: publication
title: Context Gates For Neural Machine Translation
authors: Zhaopeng Tu, Yang Liu, Zhengdong Lu, Xiaohua Liu, Hang Li
conference: Transactions of the Association for Computational Linguistics
year: 2017
bibkey: tu2016context
citations: 113
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.06043'}]
tags: ["Model Architecture", "TACL"]
short_authors: Tu et al.
---
In neural machine translation (NMT), generation of a target word depends on
both source and target contexts. We find that source contexts have a direct
impact on the adequacy of a translation while target contexts affect the
fluency. Intuitively, generation of a content word should rely more on the
source context and generation of a functional word should rely more on the
target context. Due to the lack of effective control over the influence from
source and target contexts, conventional NMT tends to yield fluent but
inadequate translations. To address this problem, we propose context gates
which dynamically control the ratios at which source and target contexts
contribute to the generation of target words. In this way, we can enhance both
the adequacy and fluency of NMT with more careful control of the information
flow from contexts. Experiments show that our approach significantly improves
upon a standard attention-based NMT system by +2.3 BLEU points.