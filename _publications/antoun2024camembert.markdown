---
layout: publication
title: 'Camembert 2.0: A Smarter French Language Model Aged To Perfection'
authors: Antoun et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: antoun2024camembert
citations: 303
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.08868'}]
tags: [Masked Language Model, Model Architecture, Tools, Training Techniques, Tokenization,
  BERT, ACL, Applications, Datasets, Language Modeling]
---
French language models, such as CamemBERT, have been widely adopted across
industries for natural language processing (NLP) tasks, with models like
CamemBERT seeing over 4 million downloads per month. However, these models face
challenges due to temporal concept drift, where outdated training data leads to
a decline in performance, especially when encountering new topics and
terminology. This issue emphasizes the need for updated models that reflect
current linguistic trends. In this paper, we introduce two new versions of the
CamemBERT base model-CamemBERTav2 and CamemBERTv2-designed to address these
challenges. CamemBERTav2 is based on the DeBERTaV3 architecture and makes use
of the Replaced Token Detection (RTD) objective for better contextual
understanding, while CamemBERTv2 is built on RoBERTa, which uses the Masked
Language Modeling (MLM) objective. Both models are trained on a significantly
larger and more recent dataset with longer context length and an updated
tokenizer that enhances tokenization performance for French. We evaluate the
performance of these models on both general-domain NLP tasks and
domain-specific applications, such as medical field tasks, demonstrating their
versatility and effectiveness across a range of use cases. Our results show
that these updated models vastly outperform their predecessors, making them
valuable tools for modern NLP systems. All our new models, as well as
intermediate checkpoints, are made openly available on Huggingface.