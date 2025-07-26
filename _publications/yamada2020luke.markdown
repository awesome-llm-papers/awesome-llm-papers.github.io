---
layout: publication
title: 'LUKE: Deep Contextualized Entity Representations With Entity-aware Self-attention'
authors: Ikuya Yamada, Akari Asai, Hiroyuki Shindo, Hideaki Takeda, Yuji Matsumoto
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: yamada2020luke
citations: 497
additional_links: [{name: Code, url: 'https://github.com/studio-ousia/luke'}, {name: Paper,
    url: 'https://arxiv.org/abs/2010.01057'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Yamada et al.
---
Entity representations are useful in natural language tasks involving
entities. In this paper, we propose new pretrained contextualized
representations of words and entities based on the bidirectional transformer.
The proposed model treats words and entities in a given text as independent
tokens, and outputs contextualized representations of them. Our model is
trained using a new pretraining task based on the masked language model of
BERT. The task involves predicting randomly masked words and entities in a
large entity-annotated corpus retrieved from Wikipedia. We also propose an
entity-aware self-attention mechanism that is an extension of the
self-attention mechanism of the transformer, and considers the types of tokens
(words or entities) when computing attention scores. The proposed model
achieves impressive empirical performance on a wide range of entity-related
tasks. In particular, it obtains state-of-the-art results on five well-known
datasets: Open Entity (entity typing), TACRED (relation classification),
CoNLL-2003 (named entity recognition), ReCoRD (cloze-style question answering),
and SQuAD 1.1 (extractive question answering). Our source code and pretrained
representations are available at https://github.com/studio-ousia/luke.