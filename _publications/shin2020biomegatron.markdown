---
layout: publication
title: 'Biomegatron: Larger Biomedical Domain Language Model'
authors: Hoo-chang Shin, Yang Zhang, Evelina Bakhturina, Raul Puri, Mostofa Patwary,
  Mohammad Shoeybi, Raghav Mani
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: shin2020biomegatron
citations: 104
additional_links: [{name: Code, url: 'https://ngc.nvidia.com]'}, {name: Code, url: 'https://github.com/NVIDIA/NeMo]'},
  {name: Paper, url: 'https://arxiv.org/abs/2010.06060'}]
tags: ["EMNLP"]
short_authors: Shin et al.
---
There has been an influx of biomedical domain-specific language models,
showing language models pre-trained on biomedical text perform better on
biomedical domain benchmarks than those trained on general domain text corpora
such as Wikipedia and Books. Yet, most works do not study the factors affecting
each domain language application deeply. Additionally, the study of model size
on domain-specific models has been mostly missing. We empirically study and
evaluate several factors that can affect performance on domain language
applications, such as the sub-word vocabulary set, model size, pre-training
corpus, and domain transfer. We show consistent improvements on benchmarks with
our larger BioMegatron model trained on a larger domain corpus, contributing to
our understanding of domain language model applications. We demonstrate
noticeable improvements over the previous state-of-the-art (SOTA) on standard
biomedical NLP benchmarks of named entity recognition, relation extraction, and
question answering. Model checkpoints and code are available at
[https://ngc.nvidia.com] and [https://github.com/NVIDIA/NeMo].