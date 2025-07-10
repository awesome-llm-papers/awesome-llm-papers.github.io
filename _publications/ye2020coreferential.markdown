---
layout: publication
title: Coreferential Reasoning Learning For Language Representation
authors: Deming Ye et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
citations: 69
bibkey: ye2020coreferential
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.06870'}, {name: Code,
    url: 'https://github.com/thunlp/CorefBERT'}]
tags: [Has Code, Model Architecture, Fine-Tuning, Training Techniques, BERT]
---
Language representation models such as BERT could effectively capture
contextual semantic information from plain text, and have been proved to
achieve promising results in lots of downstream NLP tasks with appropriate
fine-tuning. However, most existing language representation models cannot
explicitly handle coreference, which is essential to the coherent understanding
of the whole discourse. To address this issue, we present CorefBERT, a novel
language representation model that can capture the coreferential relations in
context. The experimental results show that, compared with existing baseline
models, CorefBERT can achieve significant improvements consistently on various
downstream NLP tasks that require coreferential reasoning, while maintaining
comparable performance to previous models on other common NLP tasks. The source
code and experiment details of this paper can be obtained from
https://github.com/thunlp/CorefBERT.