---
layout: publication
title: Modelling Hierarchical Structure Between Dialogue Policy And Natural Language
  Generator With Option Framework For Task-oriented Dialogue System
authors: Jianhong Wang, Yuan Zhang, Tae-kyun Kim, Yunjie Gu
conference: Arxiv
year: 2020
citations: 31
bibkey: wang2020modelling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.06814'}]
tags: [Ethics and Bias, Training Techniques, Tools, Agentic, Reinforcement Learning]
---
Designing task-oriented dialogue systems is a challenging research topic,
since it needs not only to generate utterances fulfilling user requests but
also to guarantee the comprehensibility. Many previous works trained end-to-end
(E2E) models with supervised learning (SL), however, the bias in annotated
system utterances remains as a bottleneck. Reinforcement learning (RL) deals
with the problem through using non-differentiable evaluation metrics (e.g., the
success rate) as rewards. Nonetheless, existing works with RL showed that the
comprehensibility of generated system utterances could be corrupted when
improving the performance on fulfilling user requests. In our work, we (1)
propose modelling the hierarchical structure between dialogue policy and
natural language generator (NLG) with the option framework, called HDNO, where
the latent dialogue act is applied to avoid designing specific dialogue act
representations; (2) train HDNO via hierarchical reinforcement learning (HRL),
as well as suggest the asynchronous updates between dialogue policy and NLG
during training to theoretically guarantee their convergence to a local
maximizer; and (3) propose using a discriminator modelled with language models
as an additional reward to further improve the comprehensibility. We test HDNO
on MultiWoz 2.0 and MultiWoz 2.1, the datasets on multi-domain dialogues, in
comparison with word-level E2E model trained with RL, LaRL and HDSA, showing
improvements on the performance evaluated by automatic evaluation metrics and
human evaluation. Finally, we demonstrate the semantic meanings of latent
dialogue acts to show the explanability for HDNO.