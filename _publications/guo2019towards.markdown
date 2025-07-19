---
layout: publication
title: Towards Complex Text-to-sql In Cross-domain Database With Intermediate Representation
authors: Guo et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: guo2019towards
citations: 315
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.08205'}]
tags: [Datasets, ACL, Evaluation]
---
We present a neural approach called IRNet for complex and cross-domain
Text-to-SQL. IRNet aims to address two challenges: 1) the mismatch between
intents expressed in natural language (NL) and the implementation details in
SQL; 2) the challenge in predicting columns caused by the large number of
out-of-domain words. Instead of end-to-end synthesizing a SQL query, IRNet
decomposes the synthesis process into three phases. In the first phase, IRNet
performs a schema linking over a question and a database schema. Then, IRNet
adopts a grammar-based neural model to synthesize a SemQL query which is an
intermediate representation that we design to bridge NL and SQL. Finally, IRNet
deterministically infers a SQL query from the synthesized SemQL query with
domain knowledge. On the challenging Text-to-SQL benchmark Spider, IRNet
achieves 46.7% accuracy, obtaining 19.5% absolute improvement over previous
state-of-the-art approaches. At the time of writing, IRNet achieves the first
position on the Spider leaderboard.