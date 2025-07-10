---
layout: publication
title: 'Clinical-longformer And Clinical-bigbird: Transformers For Long Clinical Sequences'
authors: Yikuan Li, Ramsey M. Wehbe, Faraz S. Ahmad, Hanyin Wang, Yuan Luo
conference: Arxiv
year: 2022
citations: 47
bibkey: li2022clinical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.11838'}, {name: Code,
    url: 'https://github.com/luoyuanlab/Clinical-Longformer]'}, {name: Code, url: 'https://huggingface.co/yikuan8/Clinical-Longformer]'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Transformer, BERT]
---
Transformers-based models, such as BERT, have dramatically improved the
performance for various natural language processing tasks. The clinical
knowledge enriched model, namely ClinicalBERT, also achieved state-of-the-art
results when performed on clinical named entity recognition and natural
language inference tasks. One of the core limitations of these transformers is
the substantial memory consumption due to their full self-attention mechanism.
To overcome this, long sequence transformer models, e.g. Longformer and
BigBird, were proposed with the idea of sparse attention mechanism to reduce
the memory usage from quadratic to the sequence length to a linear scale. These
models extended the maximum input sequence length from 512 to 4096, which
enhanced the ability of modeling long-term dependency and consequently achieved
optimal results in a variety of tasks. Inspired by the success of these long
sequence transformer models, we introduce two domain enriched language models,
namely Clinical-Longformer and Clinical-BigBird, which are pre-trained from
large-scale clinical corpora. We evaluate both pre-trained models using 10
baseline tasks including named entity recognition, question answering, and
document classification tasks. The results demonstrate that Clinical-Longformer
and Clinical-BigBird consistently and significantly outperform ClinicalBERT as
well as other short-sequence transformers in all downstream tasks. We have made
our source code available at
[https://github.com/luoyuanlab/Clinical-Longformer] the pre-trained models
available for public download at:
[https://huggingface.co/yikuan8/Clinical-Longformer].