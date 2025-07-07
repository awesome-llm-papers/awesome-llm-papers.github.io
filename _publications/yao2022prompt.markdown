---
layout: publication
title: Prompt Tuning For Discriminative Pre-trained Language Models
authors: Yuan Yao et al.
conference: Arxiv
year: 2022
citations: 26
bibkey: yao2022prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.11166'}, {name: Code,
    url: 'https://github.com/thunlp/DPT'}]
tags: [Training Techniques, Fine-Tuning, Tools, BERT, Has Code, Prompting, Language
    Modeling, Model Architecture]
---
Recent works have shown promising results of prompt tuning in stimulating
pre-trained language models (PLMs) for natural language processing (NLP) tasks.
However, to the best of our knowledge, existing works focus on prompt-tuning
generative PLMs that are pre-trained to generate target tokens, such as BERT.
It is still unknown whether and how discriminative PLMs, e.g., ELECTRA, can be
effectively prompt-tuned. In this work, we present DPT, the first prompt tuning
framework for discriminative PLMs, which reformulates NLP tasks into a
discriminative language modeling problem. Comprehensive experiments on text
classification and question answering show that, compared with vanilla
fine-tuning, DPT achieves significantly higher performance, and also prevents
the unstable problem in tuning large PLMs in both full-set and low-resource
settings. The source code and experiment details of this paper can be obtained
from https://github.com/thunlp/DPT.