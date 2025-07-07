---
layout: publication
title: 'Hyperprompt: Prompt-based Task-conditioning Of Transformers'
authors: Yun He et al.
conference: Arxiv
year: 2022
citations: 26
bibkey: he2022prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.00759'}]
tags: [Transformer, Attention Mechanism, Efficiency and Optimization, Prompting, Model
    Architecture]
---
Prompt-Tuning is a new paradigm for finetuning pre-trained language models in
a parameter-efficient way. Here, we explore the use of HyperNetworks to
generate hyper-prompts: we propose HyperPrompt, a novel architecture for
prompt-based task-conditioning of self-attention in Transformers. The
hyper-prompts are end-to-end learnable via generation by a HyperNetwork.
HyperPrompt allows the network to learn task-specific feature maps where the
hyper-prompts serve as task global memories for the queries to attend to, at
the same time enabling flexible information sharing among tasks. We show that
HyperPrompt is competitive against strong multi-task learning baselines with as
few as \\(0.14%\\) of additional task-conditioning parameters, achieving great
parameter and computational efficiency. Through extensive empirical
experiments, we demonstrate that HyperPrompt can achieve superior performances
over strong T5 multi-task learning baselines and parameter-efficient adapter
variants including Prompt-Tuning and HyperFormer++ on Natural Language
Understanding benchmarks of GLUE and SuperGLUE across many model sizes.