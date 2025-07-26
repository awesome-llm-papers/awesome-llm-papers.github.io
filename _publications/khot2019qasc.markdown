---
layout: publication
title: 'QASC: A Dataset For Question Answering Via Sentence Composition'
authors: Tushar Khot, Peter Clark, Michal Guerquin, Peter Jansen, Ashish Sabharwal
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: khot2019qasc
citations: 199
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.11473'}]
tags: ["AAAI", "Datasets"]
short_authors: Khot et al.
---
Composing knowledge from multiple pieces of texts is a key challenge in
multi-hop question answering. We present a multi-hop reasoning dataset,
Question Answering via Sentence Composition(QASC), that requires retrieving
facts from a large corpus and composing them to answer a multiple-choice
question. QASC is the first dataset to offer two desirable properties: (a) the
facts to be composed are annotated in a large corpus, and (b) the decomposition
into these facts is not evident from the question itself. The latter makes
retrieval challenging as the system must introduce new concepts or relations in
order to discover potential decompositions. Further, the reasoning model must
then learn to identify valid compositions of these retrieved facts using
common-sense reasoning. To help address these challenges, we provide annotation
for supporting facts as well as their composition. Guided by these annotations,
we present a two-step approach to mitigate the retrieval challenges. We use
other multiple-choice datasets as additional training data to strengthen the
reasoning model. Our proposed approach improves over current state-of-the-art
language models by 11% (absolute). The reasoning and retrieval problems,
however, remain unsolved as this model still lags by 20% behind human
performance.