---
layout: publication
title: Do We Still Need Clinical Language Models?
authors: Eric Lehman et al.
conference: Arxiv
year: 2023
citations: 38
bibkey: lehman2023do
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.08091'}]
tags: [Efficiency and Optimization, Training Techniques, Responsible AI, In-Context
    Learning]
---
Although recent advances in scaling large language models (LLMs) have
resulted in improvements on many NLP tasks, it remains unclear whether these
models trained primarily with general web text are the right tool in highly
specialized, safety critical domains such as clinical text. Recent results have
suggested that LLMs encode a surprising amount of medical knowledge. This
raises an important question regarding the utility of smaller domain-specific
language models. With the success of general-domain LLMs, is there still a need
for specialized clinical models? To investigate this question, we conduct an
extensive empirical analysis of 12 language models, ranging from 220M to 175B
parameters, measuring their performance on 3 different clinical tasks that test
their ability to parse and reason over electronic health records. As part of
our experiments, we train T5-Base and T5-Large models from scratch on clinical
notes from MIMIC III and IV to directly investigate the efficiency of clinical
tokens. We show that relatively small specialized clinical models substantially
outperform all in-context learning approaches, even when finetuned on limited
annotated data. Further, we find that pretraining on clinical tokens allows for
smaller, more parameter-efficient models that either match or outperform much
larger language models trained on general text. We release the code and the
models used under the PhysioNet Credentialed Health Data license and data use
agreement.