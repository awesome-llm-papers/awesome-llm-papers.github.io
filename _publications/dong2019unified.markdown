---
layout: publication
title: Unified Language Model Pre-training For Natural Language Understanding And
  Generation
authors: Li Dong, Nan Yang, Wenhui Wang, Furu Wei, Xiaodong Liu, Yu Wang, Jianfeng
  Gao, Ming Zhou, Hsiao-wuen Hon
conference: Arxiv
year: 2019
bibkey: dong2019unified
citations: 831
additional_links: [{name: Code, url: 'https://github.com/microsoft/unilm'}, {name: Paper,
    url: 'https://arxiv.org/abs/1905.03197'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Dong et al.
---
This paper presents a new Unified pre-trained Language Model (UniLM) that can
be fine-tuned for both natural language understanding and generation tasks. The
model is pre-trained using three types of language modeling tasks:
unidirectional, bidirectional, and sequence-to-sequence prediction. The unified
modeling is achieved by employing a shared Transformer network and utilizing
specific self-attention masks to control what context the prediction conditions
on. UniLM compares favorably with BERT on the GLUE benchmark, and the SQuAD 2.0
and CoQA question answering tasks. Moreover, UniLM achieves new
state-of-the-art results on five natural language generation datasets,
including improving the CNN/DailyMail abstractive summarization ROUGE-L to
40.51 (2.04 absolute improvement), the Gigaword abstractive summarization
ROUGE-L to 35.75 (0.86 absolute improvement), the CoQA generative question
answering F1 score to 82.5 (37.1 absolute improvement), the SQuAD question
generation BLEU-4 to 22.12 (3.75 absolute improvement), and the DSTC7
document-grounded dialog response generation NIST-4 to 2.67 (human performance
is 2.65). The code and pre-trained models are available at
https://github.com/microsoft/unilm.