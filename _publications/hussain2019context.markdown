---
layout: publication
title: 'Codegru: Context-aware Deep Learning With Gated Recurrent Unit For Source
  Code Modeling'
authors: Yasir Hussain, Zhiqiu Huang, Yu Zhou, Senzhang Wang
conference: Information and Software Technology. Volume 125 September 2020 106309
year: 2019
citations: 28
bibkey: hussain2019context
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.00884'}]
tags: [RAG, Applications, Training Techniques, Reinforcement Learning]
---
Recently deep learning based Natural Language Processing (NLP) models have
shown great potential in the modeling of source code. However, a major
limitation of these approaches is that they take source code as simple tokens
of text and ignore its contextual, syntactical and structural dependencies. In
this work, we present CodeGRU, a gated recurrent unit based source code
language model that is capable of capturing source code's contextual,
syntactical and structural dependencies. We introduce a novel approach which
can capture the source code context by leveraging the source code token types.
Further, we adopt a novel approach which can learn variable size context by
taking into account source code's syntax, and structural information. We
evaluate CodeGRU with real-world data set and it shows that CodeGRU outperforms
the state-of-the-art language models and help reduce the vocabulary size up to
24.93%. Unlike previous works, we tested CodeGRU with an independent test set
which suggests that our methodology does not requisite the source code comes
from the same domain as training data while providing suggestions. We further
evaluate CodeGRU with two software engineering applications: source code
suggestion, and source code completion. Our experiment confirms that the source
code's contextual information can be vital and can help improve the software
language models. The extensive evaluation of CodeGRU shows that it outperforms
the state-of-the-art models. The results further suggest that the proposed
approach can help reduce the vocabulary size and is of practical use for
software developers.