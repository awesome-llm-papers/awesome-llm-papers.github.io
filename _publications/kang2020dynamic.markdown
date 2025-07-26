---
layout: publication
title: Dynamic Context Selection For Document-level Neural Machine Translation Via
  Reinforcement Learning
authors: Xiaomian Kang, Yang Zhao, Jiajun Zhang, Chengqing Zong
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: kang2020dynamic
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.04314'}]
tags: ["EMNLP"]
short_authors: Kang et al.
---
Document-level neural machine translation has yielded attractive
improvements. However, majority of existing methods roughly use all context
sentences in a fixed scope. They neglect the fact that different source
sentences need different sizes of context. To address this problem, we propose
an effective approach to select dynamic context so that the document-level
translation model can utilize the more useful selected context sentences to
produce better translations. Specifically, we introduce a selection module that
is independent of the translation module to score each candidate context
sentence. Then, we propose two strategies to explicitly select a variable
number of context sentences and feed them into the translation module. We train
the two modules end-to-end via reinforcement learning. A novel reward is
proposed to encourage the selection and utilization of dynamic context
sentences. Experiments demonstrate that our approach can select adaptive
context sentences for different source sentences, and significantly improves
the performance of document-level translation methods.