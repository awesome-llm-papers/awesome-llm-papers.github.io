---
layout: publication
title: 'Urls Help, Topics Guide: Understanding Metadata Utility In LLM Training'
authors: "Fan Dongyang, Sabol\u010Dec Vinko, Jaggi Martin"
conference: Proceedings of the IEEE/ACM 46th International Conference on Software
  Engineering
year: 2025
bibkey: fan2025urls
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.16570'}]
tags: [Prompting, Training Techniques, Efficiency And Optimization, Evaluation, LLM
    For Code, LLM for Code, Reinforcement Learning, Alt]
---
Large Language Models (LLMs) are commonly pretrained on vast corpora of text without utilizing contextual metadata such as source, quality, or topic, leading to a context-free learning paradigm. While recent studies suggest that adding metadata like URL information as context (i.e., auxiliary inputs not used in the loss calculation) can improve training efficiency and downstream performance, they offer limited understanding of which types of metadata are truly effective and under what conditions. In this work, we conduct a systematic evaluation and find that not all metadata types contribute equally. Only URL context speeds up training, whereas quality scores and topic/format domain information offer no clear benefit. Furthermore, the improved downstream performances of URL conditioning emerge only when longer prompts are used at inference time. In addition, we demonstrate that context-aware pretraining enables more controllable generation than context-free pretraining, in a classifier-free guidance fashion. Although topic and format metadata do not accelerate training, they are effective for steering outputs, offering human-interpretable control over generation.