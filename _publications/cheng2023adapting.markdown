---
layout: publication
title: Adapting Large Language Models Via Reading Comprehension
authors: Daixuan Cheng, Shaohan Huang, Furu Wei
conference: No Venue
year: 2023
bibkey: cheng2023adapting
additional_links: [{name: Code, url: 'https://github.com/microsoft/LMOps'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/650912727e0d56c27157af5f'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2309.09530'}]
tags: ["Training Techniques"]
short_authors: Daixuan Cheng, Shaohan Huang, Furu Wei
---
We explore how continued pre-training on domain-specific corpora influences large language models, revealing that training on the raw corpora endows the model with domain knowledge, but drastically hurts its prompting ability for question answering. Taken inspiration from human learning via reading comprehension--practice after reading improves the ability to answer questions based on the learned knowledge--we propose a simple method for transforming raw corpora into reading comprehension texts. Each raw text is enriched with a series of tasks related to its content. Our method, highly scalable and applicable to any pre-training corpora, consistently enhances performance across various tasks in three different domains: biomedicine, finance, and law. Notably, our 7B language model achieves competitive performance with domain-specific models of much larger scales, such as BloombergGPT-50B. Furthermore, we demonstrate that domain-specific reading comprehension texts can improve the model's performance even on general benchmarks, showing the potential to develop a general model across even more domains. Our model, code, and data will be available at https://github.com/microsoft/LMOps.

https://huggingface.co/discussions/paper/650912727e0d56c27157af5f