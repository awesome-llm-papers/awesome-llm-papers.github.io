---
layout: publication
title: Few-shot Knowledge Graph-to-text Generation With Pretrained Language Models
authors: Junyi Li et al.
conference: Arxiv
year: 2021
citations: 16
bibkey: li2021few
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01623'}, {name: Code,
    url: 'https://github.com/RUCAIBox/Few-Shot-KG2Text'}]
tags: [Ethics and Bias, RAG, Few-Shot, Has Code, Language Modeling]
---
This paper studies how to automatically generate a natural language text that
describes the facts in knowledge graph (KG). Considering the few-shot setting,
we leverage the excellent capacities of pretrained language models (PLMs) in
language understanding and generation. We make three major technical
contributions, namely representation alignment for bridging the semantic gap
between KG encodings and PLMs, relation-biased KG linearization for deriving
better input representations, and multi-task learning for learning the
correspondence between KG and text. Extensive experiments on three benchmark
datasets have demonstrated the effectiveness of our model on KG-to-text
generation task. In particular, our model outperforms all comparison methods on
both fully-supervised and few-shot settings. Our code and datasets are
available at https://github.com/RUCAIBox/Few-Shot-KG2Text.