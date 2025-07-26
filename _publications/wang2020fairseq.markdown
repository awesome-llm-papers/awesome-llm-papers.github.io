---
layout: publication
title: 'Fairseq S2T: Fast Speech-to-text Modeling With Fairseq'
authors: Changhan Wang, Yun Tang, Xutai Ma, Anne Wu, Sravya Popuri, Dmytro Okhonko,
  Juan Pino
conference: Arxiv
year: 2020
bibkey: wang2020fairseq
citations: 95
additional_links: [{name: Code, url: 'https://github.com/pytorch/fairseq/tree/master/examples/speech_to_text'},
  {name: Paper, url: 'https://arxiv.org/abs/2010.05171'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Wang et al.
---
We introduce fairseq S2T, a fairseq extension for speech-to-text (S2T)
modeling tasks such as end-to-end speech recognition and speech-to-text
translation. It follows fairseq's careful design for scalability and
extensibility. We provide end-to-end workflows from data pre-processing, model
training to offline (online) inference. We implement state-of-the-art
RNN-based, Transformer-based as well as Conformer-based models and open-source
detailed training recipes. Fairseq's machine translation models and language
models can be seamlessly integrated into S2T workflows for multi-task learning
or transfer learning. Fairseq S2T documentation and examples are available at
https://github.com/pytorch/fairseq/tree/master/examples/speech_to_text.