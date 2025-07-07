---
layout: publication
title: 'Sentence-t5: Scalable Sentence Encoders From Pre-trained Text-to-text Models'
authors: Jianmo Ni et al.
conference: Arxiv
year: 2021
citations: 117
bibkey: ni2021sentence
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.08877'}, {name: Code,
    url: 'https://tfhub.dev/google/collections/sentence-t5/1'}]
tags: [Transformer, Fine-Tuning, Reinforcement Learning, BERT, Has Code, Model Architecture]
---
We provide the first exploration of sentence embeddings from text-to-text
transformers (T5). Sentence embeddings are broadly useful for language
processing tasks. While T5 achieves impressive performance on language tasks
cast as sequence-to-sequence mapping problems, it is unclear how to produce
sentence embeddings from encoder-decoder models. We investigate three methods
for extracting T5 sentence embeddings: two utilize only the T5 encoder and one
uses the full T5 encoder-decoder model. To support our investigation, we
establish a new sentence representation transfer benchmark, SentGLUE, which
extends the SentEval toolkit to nine tasks from the GLUE benchmark. Our
encoder-only models outperforms Sentence-BERT and SimCSE sentence embeddings on
both SentEval and SentGLUE transfer tasks, including semantic textual
similarity (STS). Scaling up T5 from millions to billions of parameters is
found to produce consistent further improvements. Finally, our encoder-decoder
method achieves a new state-of-the-art on STS when using sentence embeddings.
Our models are released at https://tfhub.dev/google/collections/sentence-t5/1.