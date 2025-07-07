---
layout: publication
title: Prototypical Verbalizer For Prompt-based Few-shot Tuning
authors: Ganqu Cui, Shengding Hu, Ning Ding, Longtao Huang, Zhiyuan Liu
conference: Arxiv
year: 2022
citations: 33
bibkey: cui2022prototypical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.09770'}, {name: Code,
    url: 'https://github.com/thunlp/OpenPrompt'}]
tags: [Training Techniques, Few-Shot, Fine-Tuning, Has Code, Prompting]
---
Prompt-based tuning for pre-trained language models (PLMs) has shown its
effectiveness in few-shot learning. Typically, prompt-based tuning wraps the
input text into a cloze question. To make predictions, the model maps the
output words to labels via a verbalizer, which is either manually designed or
automatically built. However, manual verbalizers heavily depend on
domain-specific prior knowledge and human efforts, while finding appropriate
label words automatically still remains challenging.In this work, we propose
the prototypical verbalizer (ProtoVerb) which is built directly from training
data. Specifically, ProtoVerb learns prototype vectors as verbalizers by
contrastive learning. In this way, the prototypes summarize training instances
and are able to enclose rich class-level semantics. We conduct experiments on
both topic classification and entity typing tasks, and the results demonstrate
that ProtoVerb significantly outperforms current automatic verbalizers,
especially when training data is extremely scarce. More surprisingly, ProtoVerb
consistently boosts prompt-based tuning even on untuned PLMs, indicating an
elegant non-tuning way to utilize PLMs. Our codes are avaliable at
https://github.com/thunlp/OpenPrompt.