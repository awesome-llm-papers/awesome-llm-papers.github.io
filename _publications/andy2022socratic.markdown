---
layout: publication
title: 'Socratic Models: Composing Zero-shot Multimodal Reasoning With Language'
authors: [andy Zeng, maria Attarian, brian Ichter, krzysztof Choromanski, adrian Wong,
  stefan Welker, federico Tombari, aveek Purohit, michael Ryoo, vikas Sindhwani, johnny
    Lee, vincent Vanhoucke, pete Florence]
conference: Arxiv
year: 2022
bibkey: andy2022socratic
citations: 143
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2204.00598v2'}]
tags: ["Applications"]
short_authors: Zeng et al.
---
Large pretrained (e.g., "foundation") models exhibit distinct capabilities
depending on the domain of data they are trained on. While these domains are
generic, they may only barely overlap. For example, visual-language models
(VLMs) are trained on Internet-scale image captions, but large language models
(LMs) are further trained on Internet-scale text with no images (e.g.,
spreadsheets, SAT questions, code). As a result, these models store different
forms of commonsense knowledge across different domains. In this work, we show
that this diversity is symbiotic, and can be leveraged through Socratic Models
(SMs): a modular framework in which multiple pretrained models may be composed
zero-shot i.e., via multimodal-informed prompting, to exchange information with
each other and capture new multimodal capabilities, without requiring
finetuning. With minimal engineering, SMs are not only competitive with
state-of-the-art zero-shot image captioning and video-to-text retrieval, but
also enable new applications such as (i) answering free-form questions about
egocentric video, (ii) engaging in multimodal assistive dialogue with people
(e.g., for cooking recipes) by interfacing with external APIs and databases
(e.g., web search), and (iii) robot perception and planning.