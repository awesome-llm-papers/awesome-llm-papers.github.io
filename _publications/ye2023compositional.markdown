---
layout: publication
title: Compositional Exemplars For In-context Learning
authors: Jiacheng Ye, Zhiyong Wu, Jiangtao Feng, Tao Yu, Lingpeng Kong
conference: Arxiv
year: 2023
citations: 24
bibkey: ye2023compositional
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.05698'}, {name: Code,
    url: 'https://github.com/HKUNLP/icl-ceil'}]
tags: [Has Code, In-Context Learning, Prompting]
---
Large pretrained language models (LMs) have shown impressive In-Context
Learning (ICL) ability, where the model learns to do an unseen task via a
prompt consisting of input-output examples as the demonstration, without any
parameter updates. The performance of ICL is highly dominated by the quality of
the selected in-context examples. However, previous selection methods are
mostly based on simple heuristics, leading to sub-optimal performance. In this
work, we formulate in-context example selection as a subset selection problem.
We propose CEIL (Compositional Exemplars for In-context Learning), which is
instantiated by Determinantal Point Processes (DPPs) to model the interaction
between the given input and in-context examples, and optimized through a
carefully-designed contrastive learning objective to obtain preference from
LMs. We validate CEIL on 12 classification and generation datasets from 7
distinct NLP tasks, including sentiment analysis, paraphrase detection, natural
language inference, commonsense reasoning, open-domain question answering, code
generation, and semantic parsing. Extensive experiments demonstrate not only
the state-of-the-art performance but also the transferability and
compositionality of CEIL, shedding new light on effective and efficient
in-context learning. Our code is released at
https://github.com/HKUNLP/icl-ceil.