---
layout: publication
title: Towards Faithful Neural Table-to-text Generation With Content-matching Constraints
authors: Wang et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: wang2020towards
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00969'}]
tags: [Model Architecture, Tools, Evaluation, ACL, Transformer, Language Modeling]
---
Text generation from a knowledge base aims to translate knowledge triples to
natural language descriptions. Most existing methods ignore the faithfulness
between a generated text description and the original table, leading to
generated information that goes beyond the content of the table. In this paper,
for the first time, we propose a novel Transformer-based generation framework
to achieve the goal. The core techniques in our method to enforce faithfulness
include a new table-text optimal-transport matching loss and a table-text
embedding similarity loss based on the Transformer model. Furthermore, to
evaluate faithfulness, we propose a new automatic metric specialized to the
table-to-text generation problem. We also provide detailed analysis on each
component of our model in our experiments. Automatic and human evaluations show
that our framework can significantly outperform state-of-the-art by a large
margin.