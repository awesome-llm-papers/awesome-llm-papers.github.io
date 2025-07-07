---
layout: publication
title: 'LERT: A Linguistically-motivated Pre-trained Language Model'
authors: Yiming Cui, Wanxiang Che, Shijin Wang, Ting Liu
conference: Arxiv
year: 2022
citations: 23
bibkey: cui2022linguistically
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.05344'}, {name: Code,
    url: 'https://github.com/ymcui/LERT'}]
tags: [Masked Language Model, Training Techniques, Pre-Training, BERT, Has Code]
---
Pre-trained Language Model (PLM) has become a representative foundation model
in the natural language processing field. Most PLMs are trained with
linguistic-agnostic pre-training tasks on the surface form of the text, such as
the masked language model (MLM). To further empower the PLMs with richer
linguistic features, in this paper, we aim to propose a simple but effective
way to learn linguistic features for pre-trained language models. We propose
LERT, a pre-trained language model that is trained on three types of linguistic
features along with the original MLM pre-training task, using a
linguistically-informed pre-training (LIP) strategy. We carried out extensive
experiments on ten Chinese NLU tasks, and the experimental results show that
LERT could bring significant improvements over various comparable baselines.
Furthermore, we also conduct analytical experiments in various linguistic
aspects, and the results prove that the design of LERT is valid and effective.
Resources are available at https://github.com/ymcui/LERT