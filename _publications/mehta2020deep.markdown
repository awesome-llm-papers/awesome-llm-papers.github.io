---
layout: publication
title: 'Delight: Deep And Light-weight Transformer'
authors: Sachin Mehta, Marjan Ghazvininejad, Srinivasan Iyer, Luke Zettlemoyer, Hannaneh
  Hajishirzi
conference: Arxiv
year: 2020
citations: 44
bibkey: mehta2020deep
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.00623'}, {name: Code,
    url: 'https://github.com/sacmehta/delight'}]
tags: [Transformer, RAG, Has Code, Language Modeling, Model Architecture]
---
We introduce a deep and light-weight transformer, DeLighT, that delivers
similar or better performance than standard transformer-based models with
significantly fewer parameters. DeLighT more efficiently allocates parameters
both (1) within each Transformer block using the DeLighT transformation, a deep
and light-weight transformation, and (2) across blocks using block-wise
scaling, which allows for shallower and narrower DeLighT blocks near the input
and wider and deeper DeLighT blocks near the output. Overall, DeLighT networks
are 2.5 to 4 times deeper than standard transformer models and yet have fewer
parameters and operations. Experiments on benchmark machine translation and
language modeling tasks show that DeLighT matches or improves the performance
of baseline Transformers with 2 to 3 times fewer parameters on average. Our
source code is available at: https://github.com/sacmehta/delight