---
layout: publication
title: 'Table-to-text: Describing Table Region With Natural Language'
authors: Bao et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: bao2018table
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.11234'}]
tags: [RAG, AAAI, Datasets]
---
In this paper, we present a generative model to generate a natural language
sentence describing a table region, e.g., a row. The model maps a row from a
table to a continuous vector and then generates a natural language sentence by
leveraging the semantics of a table. To deal with rare words appearing in a
table, we develop a flexible copying mechanism that selectively replicates
contents from the table in the output sequence. Extensive experiments
demonstrate the accuracy of the model and the power of the copying mechanism.
On two synthetic datasets, WIKIBIO and SIMPLEQUESTIONS, our model improves the
current state-of-the-art BLEU-4 score from 34.70 to 40.26 and from 33.32 to
39.12, respectively. Furthermore, we introduce an open-domain dataset
WIKITABLETEXT including 13,318 explanatory sentences for 4,962 tables. Our
model achieves a BLEU-4 score of 38.23, which outperforms template based and
language model based approaches.