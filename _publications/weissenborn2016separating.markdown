---
layout: publication
title: Separating Answers From Queries For Neural Reading Comprehension
authors: Dirk Weissenborn
conference: Arxiv
year: 2016
citations: 18
bibkey: weissenborn2016separating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.03316'}]
tags: [Reinforcement Learning, RAG, Model Architecture, Evaluation]
---
We present a novel neural architecture for answering queries, designed to
optimally leverage explicit support in the form of query-answer memories. Our
model is able to refine and update a given query while separately accumulating
evidence for predicting the answer. Its architecture reflects this separation
with dedicated embedding matrices and loosely connected information pathways
(modules) for updating the query and accumulating evidence. This separation of
responsibilities effectively decouples the search for query related support and
the prediction of the answer. On recent benchmark datasets for reading
comprehension, our model achieves state-of-the-art results. A qualitative
analysis reveals that the model effectively accumulates weighted evidence from
the query and over multiple support retrieval cycles which results in a robust
answer prediction.