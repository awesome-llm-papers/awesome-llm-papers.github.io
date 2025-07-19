---
layout: publication
title: Encoding Database Schemas With Relation-aware Self-attention For Text-to-sql
  Parsers
authors: Shin Richard
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: shin2019encoding
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.11790'}]
tags: [Model Architecture, Training Techniques, ACL, Transformer, Datasets, Reinforcement
    Learning, Attention Mechanism]
---
When translating natural language questions into SQL queries to answer
questions from a database, we would like our methods to generalize to domains
and database schemas outside of the training set. To handle complex questions
and database schemas with a neural encoder-decoder paradigm, it is critical to
properly encode the schema as part of the input with the question. In this
paper, we use relation-aware self-attention within the encoder so that it can
reason about how the tables and columns in the provided schema relate to each
other and use this information in interpreting the question. We achieve
significant gains on the recently-released Spider dataset with 42.94% exact
match accuracy, compared to the 18.96% reported in published work.