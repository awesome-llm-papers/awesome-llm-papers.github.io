---
layout: publication
title: 'Openprompt: An Open-source Framework For Prompt-learning'
authors: Ning Ding, Shengding Hu, Weilin Zhao, Yulin Chen, Zhiyuan Liu, Hai-tao Zheng,
  Maosong Sun
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics: System Demonstrations'
year: 2022
bibkey: ding2021openprompt
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.01998'}]
tags: ["Has Code", "Prompting", "Tools"]
short_authors: Ding et al.
---
Prompt-learning has become a new paradigm in modern natural language
processing, which directly adapts pre-trained language models (PLMs) to
\\(cloze\\)-style prediction, autoregressive modeling, or sequence to sequence
generation, resulting in promising performances on various tasks. However, no
standard implementation framework of prompt-learning is proposed yet, and most
existing prompt-learning codebases, often unregulated, only provide limited
implementations for specific scenarios. Since there are many details such as
templating strategy, initializing strategy, and verbalizing strategy, etc. need
to be considered in prompt-learning, practitioners face impediments to quickly
adapting the desired prompt learning methods to their applications. In this
paper, we present \{OpenPrompt\}, a unified easy-to-use toolkit to conduct
prompt-learning over PLMs. OpenPrompt is a research-friendly framework that is
equipped with efficiency, modularity, and extendibility, and its combinability
allows the freedom to combine different PLMs, task formats, and prompting
modules in a unified paradigm. Users could expediently deploy prompt-learning
frameworks and evaluate the generalization of them on different NLP tasks
without constraints. OpenPrompt is publicly released at \{\url\{
https://github.com/thunlp/OpenPrompt\}\}.