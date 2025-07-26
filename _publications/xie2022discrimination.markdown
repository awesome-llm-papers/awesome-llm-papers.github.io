---
layout: publication
title: 'From Discrimination To Generation: Knowledge Graph Completion With Generative
  Transformer'
authors: Xin Xie, Ningyu Zhang, Zhoubo Li, Shumin Deng, Hui Chen, Feiyu Xiong, Mosha
  Chen, Huajun Chen
conference: Companion Proceedings of the Web Conference 2022
year: 2022
bibkey: xie2022discrimination
citations: 60
additional_links: [{name: Code, url: 'https://github.com/zjunlp/PromptKG/tree/main/GenKGC'},
  {name: Paper, url: 'https://arxiv.org/abs/2202.02113'}]
tags: ["Datasets", "Has Code", "Model Architecture"]
short_authors: Xie et al.
---
Knowledge graph completion aims to address the problem of extending a KG with
missing triples. In this paper, we provide an approach GenKGC, which converts
knowledge graph completion to sequence-to-sequence generation task with the
pre-trained language model. We further introduce relation-guided demonstration
and entity-aware hierarchical decoding for better representation learning and
fast inference. Experimental results on three datasets show that our approach
can obtain better or comparable performance than baselines and achieve faster
inference speed compared with previous methods with pre-trained language
models. We also release a new large-scale Chinese knowledge graph dataset
AliopenKG500 for research purpose. Code and datasets are available in
https://github.com/zjunlp/PromptKG/tree/main/GenKGC.