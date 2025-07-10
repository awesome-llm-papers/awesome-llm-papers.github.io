---
layout: publication
title: 'Dspy: Compiling Declarative Language Model Calls Into Self-improving Pipelines'
authors: Omar Khattab et al.
conference: Arxiv
year: 2023
citations: 18
bibkey: khattab2023compiling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.03714'}, {name: Code,
    url: 'https://github.com/stanfordnlp/dspy'}]
tags: [Has Code, Model Architecture, Few-Shot, Tools, Prompting, Agentic, GPT]
---
The ML community is rapidly exploring techniques for prompting language
models (LMs) and for stacking them into pipelines that solve complex tasks.
Unfortunately, existing LM pipelines are typically implemented using hard-coded
"prompt templates", i.e. lengthy strings discovered via trial and error. Toward
a more systematic approach for developing and optimizing LM pipelines, we
introduce DSPy, a programming model that abstracts LM pipelines as text
transformation graphs, i.e. imperative computational graphs where LMs are
invoked through declarative modules. DSPy modules are parameterized, meaning
they can learn (by creating and collecting demonstrations) how to apply
compositions of prompting, finetuning, augmentation, and reasoning techniques.
We design a compiler that will optimize any DSPy pipeline to maximize a given
metric. We conduct two case studies, showing that succinct DSPy programs can
express and optimize sophisticated LM pipelines that reason about math word
problems, tackle multi-hop retrieval, answer complex questions, and control
agent loops. Within minutes of compiling, a few lines of DSPy allow GPT-3.5 and
llama2-13b-chat to self-bootstrap pipelines that outperform standard few-shot
prompting (generally by over 25% and 65%, respectively) and pipelines with
expert-created demonstrations (by up to 5-46% and 16-40%, respectively). On top
of that, DSPy programs compiled to open and relatively small LMs like
770M-parameter T5 and llama2-13b-chat are competitive with approaches that rely
on expert-written prompt chains for proprietary GPT-3.5. DSPy is available at
https://github.com/stanfordnlp/dspy