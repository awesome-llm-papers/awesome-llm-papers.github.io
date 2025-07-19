---
layout: publication
title: 'Doc2dict: Information Extraction As Text Generation'
authors: Townsend et al.
conference: Mining Text Data
year: 2021
bibkey: townsend2021doc2dict
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.07510'}]
tags: [Model Architecture, Language Modeling, Transformer]
---
Typically, information extraction (IE) requires a pipeline approach: first, a
sequence labeling model is trained on manually annotated documents to extract
relevant spans; then, when a new document arrives, a model predicts spans which
are then post-processed and standardized to convert the information into a
database entry. We replace this labor-intensive workflow with a transformer
language model trained on existing database records to directly generate
structured JSON. Our solution removes the workload associated with producing
token-level annotations and takes advantage of a data source which is generally
quite plentiful (e.g. database records). As long documents are common in
information extraction tasks, we use gradient checkpointing and chunked
encoding to apply our method to sequences of up to 32,000 tokens on a single
GPU. Our Doc2Dict approach is competitive with more complex, hand-engineered
pipelines and offers a simple but effective baseline for document-level
information extraction. We release our Doc2Dict model and code to reproduce our
experiments and facilitate future work.