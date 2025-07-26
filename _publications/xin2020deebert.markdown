---
layout: publication
title: 'Deebert: Dynamic Early Exiting For Accelerating BERT Inference'
authors: Ji Xin, Raphael Tang, Jaejun Lee, Yaoliang Yu, Jimmy Lin
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: xin2020deebert
citations: 253
additional_links: [{name: Code, url: 'https://github.com/castorini/DeeBERT'}, {name: Paper,
    url: 'https://arxiv.org/abs/2004.12993'}]
tags: ["Model Architecture"]
short_authors: Xin et al.
---
Large-scale pre-trained language models such as BERT have brought significant
improvements to NLP applications. However, they are also notorious for being
slow in inference, which makes them difficult to deploy in real-time
applications. We propose a simple but effective method, DeeBERT, to accelerate
BERT inference. Our approach allows samples to exit earlier without passing
through the entire model. Experiments show that DeeBERT is able to save up to
~40% inference time with minimal degradation in model quality. Further analyses
show different behaviors in the BERT transformer layers and also reveal their
redundancy. Our work provides new ideas to efficiently apply deep
transformer-based models to downstream tasks. Code is available at
https://github.com/castorini/DeeBERT.