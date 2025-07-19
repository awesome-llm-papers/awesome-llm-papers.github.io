---
layout: publication
title: Learning To Plan Long-term For Language Modeling
authors: Mai Florian, Cornille Nathan, Moens Marie-francine
conference: Automation in Construction
year: 2024
bibkey: mai2024learning
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.00070'}]
tags: [Model Architecture, Language Modeling, Attention Mechanism]
---
Modern language models predict the next token in the sequence by considering
the past text through a powerful function such as attention. However, language
models have no explicit mechanism that allows them to spend computation time
for planning long-distance future text, leading to a suboptimal token
prediction. In this paper, we propose a planner that predicts a latent plan for
many sentences into the future. By sampling multiple plans at once, we
condition the language model on an accurate approximation of the distribution
of text continuations, which leads to better next token prediction accuracy. In
effect, this allows trading computation time for prediction accuracy.