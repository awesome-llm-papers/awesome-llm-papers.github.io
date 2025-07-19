---
layout: publication
title: End-to-end Trainable Retrieval-augmented Generation For Relation Extraction
authors: Makino Kohei, Miwa Makoto, Sasaki Yutaka
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2021'
year: 2024
bibkey: makino2024end
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.03790'}]
tags: [Training Techniques, Efficiency And Optimization, Evaluation, ACL, EMNLP, Applications,
  RAG, Datasets, Language Modeling]
---
This paper addresses a crucial challenge in retrieval-augmented
generation-based relation extractors; the end-to-end training is not applicable
to conventional retrieval-augmented generation due to the non-differentiable
nature of instance retrieval. This problem prevents the instance retrievers
from being optimized for the relation extraction task, and conventionally it
must be trained with an objective different from that for relation extraction.
To address this issue, we propose a novel End-to-end Trainable
Retrieval-Augmented Generation (ETRAG), which allows end-to-end optimization of
the entire model, including the retriever, for the relation extraction
objective by utilizing a differentiable selection of the \\(k\\) nearest instances.
We evaluate the relation extraction performance of ETRAG on the TACRED dataset,
which is a standard benchmark for relation extraction. ETRAG demonstrates
consistent improvements against the baseline model as retrieved instances are
added. Furthermore, the analysis of instances retrieved by the end-to-end
trained retriever confirms that the retrieved instances contain common relation
labels or entities with the query and are specialized for the target task. Our
findings provide a promising foundation for future research on
retrieval-augmented generation and the broader applications of text generation
in Natural Language Processing.