---
layout: publication
title: 'SGPT: GPT Sentence Embeddings For Semantic Search'
authors: Niklas Muennighoff
conference: Arxiv
year: 2022
citations: 46
bibkey: muennighoff2022gpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.08904'}, {name: Code,
    url: 'https://github.com/Muennighoff/sgpt'}]
tags: [Training Techniques, Transformer, GPT, Fine-Tuning, Has Code, Prompting, Model
    Architecture]
---
Decoder transformers have continued increasing in scale reaching hundreds of
billions of parameters. Due to their scale the same decoder sets
state-of-the-art results on various language tasks via prompting or
fine-tuning. Yet, these large foundation models remain unusable for the related
fields of semantic search and sentence embeddings. This prevents possibly new
state-of-the-art results and forces organizations to train and maintain
separate models. To this end, we propose SGPT to use decoders for sentence
embeddings and semantic search via prompting or fine-tuning. At 5.8 billion
parameters SGPT improves on the previously best sentence embeddings by a margin
of 7% and outperforms a concurrent method with 175 billion parameters as
measured on the BEIR search benchmark. Code, models and result files are freely
available at https://github.com/Muennighoff/sgpt.