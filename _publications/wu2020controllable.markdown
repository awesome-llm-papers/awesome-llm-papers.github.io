---
layout: publication
title: A Controllable Model Of Grounded Response Generation
authors: Zeqiu Wu et al.
conference: Arxiv
year: 2020
citations: 16
bibkey: wu2020controllable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00613'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Tools]
---
Current end-to-end neural conversation models inherently lack the flexibility
to impose semantic control in the response generation process, often resulting
in uninteresting responses. Attempts to boost informativeness alone come at the
expense of factual accuracy, as attested by pretrained language models'
propensity to "hallucinate" facts. While this may be mitigated by access to
background knowledge, there is scant guarantee of relevance and informativeness
in generated responses. We propose a framework that we call controllable
grounded response generation (CGRG), in which lexical control phrases are
either provided by a user or automatically extracted by a control phrase
predictor from dialogue context and grounding knowledge. Quantitative and
qualitative results show that, using this framework, a transformer based model
with a novel inductive attention mechanism, trained on a conversation-like
Reddit dataset, outperforms strong generation baselines.