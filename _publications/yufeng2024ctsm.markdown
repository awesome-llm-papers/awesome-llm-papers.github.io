---
layout: publication
title: 'CTSM: Combining Trait And State Emotions For Empathetic Response Model'
authors: Yufeng et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: yufeng2024ctsm
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.15516'}]
tags: [Evaluation, EMNLP]
---
Empathetic response generation endeavors to empower dialogue systems to
perceive speakers' emotions and generate empathetic responses accordingly.
Psychological research demonstrates that emotion, as an essential factor in
empathy, encompasses trait emotions, which are static and context-independent,
and state emotions, which are dynamic and context-dependent. However, previous
studies treat them in isolation, leading to insufficient emotional perception
of the context, and subsequently, less effective empathetic expression. To
address this problem, we propose Combining Trait and State emotions for
Empathetic Response Model (CTSM). Specifically, to sufficiently perceive
emotions in dialogue, we first construct and encode trait and state emotion
embeddings, and then we further enhance emotional perception capability through
an emotion guidance module that guides emotion representation. In addition, we
propose a cross-contrastive learning decoder to enhance the model's empathetic
expression capability by aligning trait and state emotions between generated
responses and contexts. Both automatic and manual evaluation results
demonstrate that CTSM outperforms state-of-the-art baselines and can generate
more empathetic responses. Our code is available at
https://github.com/wangyufeng-empty/CTSM