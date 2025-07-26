---
layout: publication
title: 'Musique: Multihop Questions Via Single-hop Question Composition'
authors: Harsh Trivedi, Niranjan Balasubramanian, Tushar Khot, Ashish Sabharwal
conference: Transactions of the Association for Computational Linguistics
year: 2022
bibkey: trivedi2021musique
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.00573'}]
tags: ["TACL"]
short_authors: Trivedi et al.
---
Multihop reasoning remains an elusive goal as existing multihop benchmarks
are known to be largely solvable via shortcuts. Can we create a question
answering (QA) dataset that, by construction, *requires* proper multihop
reasoning? To this end, we introduce a bottom-up approach that systematically
selects composable pairs of single-hop questions that are connected, i.e.,
where one reasoning step critically relies on information from another. This
bottom-up methodology lets us explore a vast space of questions and add
stringent filters as well as other mechanisms targeting connected reasoning. It
provides fine-grained control over the construction process and the properties
of the resulting \\(k\\)-hop questions. We use this methodology to create
MuSiQue-Ans, a new multihop QA dataset with 25K 2-4 hop questions. Relative to
existing datasets, MuSiQue-Ans is more difficult overall (3x increase in
human-machine gap), and harder to cheat via disconnected reasoning (e.g., a
single-hop model has a 30 point drop in F1). We further add unanswerable
contrast questions to produce a more stringent dataset, MuSiQue-Full. We hope
our datasets will help the NLP community develop models that perform genuine
multihop reasoning.