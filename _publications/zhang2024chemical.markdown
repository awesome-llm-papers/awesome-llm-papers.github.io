---
layout: publication
title: 'Chemllm: A Chemical Large Language Model'
authors: Di Zhang et al.
conference: Arxiv
year: 2024
citations: 24
bibkey: zhang2024chemical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.06852'}, {name: Code,
    url: 'https://hf.co/AI4Chem'}]
tags: [GPT, Fine-Tuning, Tools, Has Code, Applications, Model Architecture]
---
Large language models (LLMs) have made impressive progress in chemistry
applications. However, the community lacks an LLM specifically designed for
chemistry. The main challenges are two-fold: firstly, most chemical data and
scientific knowledge are stored in structured databases, which limits the
model's ability to sustain coherent dialogue when used directly. Secondly,
there is an absence of objective and fair benchmark that encompass most
chemistry tasks. Here, we introduce ChemLLM, a comprehensive framework that
features the first LLM dedicated to chemistry. It also includes ChemData, a
dataset specifically designed for instruction tuning, and ChemBench, a robust
benchmark covering nine essential chemistry tasks. ChemLLM is adept at
performing various tasks across chemical disciplines with fluid dialogue
interaction. Notably, ChemLLM achieves results comparable to GPT-4 on the core
chemical tasks and demonstrates competitive performance with LLMs of similar
size in general scenarios. ChemLLM paves a new path for exploration in chemical
studies, and our method of incorporating structured chemical knowledge into
dialogue systems sets a new standard for developing LLMs in various scientific
fields. Codes, Datasets, and Model weights are publicly accessible at
https://hf.co/AI4Chem