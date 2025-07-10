---
layout: publication
title: 'Mention Memory: Incorporating Textual Knowledge Into Transformers Through
  Entity Mention Attention'
authors: Michiel De Jong, Yury Zemlyanskiy, Nicholas Fitzgerald, Fei Sha, William
  Cohen
conference: Arxiv
year: 2021
citations: 18
bibkey: dejong2021mention
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.06176'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Training Techniques,
  Evaluation]
---
Natural language understanding tasks such as open-domain question answering
often require retrieving and assimilating factual information from multiple
sources. We propose to address this problem by integrating a semi-parametric
representation of a large text corpus into a Transformer model as a source of
factual knowledge. Specifically, our method represents knowledge with `mention
memory', a table of dense vector representations of every entity mention in a
corpus. The proposed model - TOME - is a Transformer that accesses the
information through internal memory layers in which each entity mention in the
input passage attends to the mention memory. This approach enables synthesis of
and reasoning over many disparate sources of information within a single
Transformer model. In experiments using a memory of 150 million Wikipedia
mentions, TOME achieves strong performance on several open-domain
knowledge-intensive tasks, including the claim verification benchmarks HoVer
and FEVER and several entity-based QA benchmarks. We also show that the model
learns to attend to informative mentions without any direct supervision.
Finally we demonstrate that the model can generalize to new unseen entities by
updating the memory without retraining.