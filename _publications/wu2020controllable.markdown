---
layout: publication
title: A Controllable Model Of Grounded Response Generation
authors: Zeqiu Wu, Michel Galley, Chris Brockett, Yizhe Zhang, Xiang Gao, Chris Quirk,
  Rik Koncel-kedziorski, Jianfeng Gao, Hannaneh Hajishirzi, Mari Ostendorf, Bill Dolan
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: wu2020controllable
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00613'}]
tags: ["AAAI"]
short_authors: Wu et al.
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