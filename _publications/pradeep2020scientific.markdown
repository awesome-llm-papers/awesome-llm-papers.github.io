---
layout: publication
title: Scientific Claim Verification With VERT5ERINI
authors: Ronak Pradeep, Xueguang Ma, Rodrigo Nogueira, Jimmy Lin
conference: Arxiv
year: 2020
citations: 33
bibkey: pradeep2020scientific
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11930'}]
tags: [Reinforcement Learning]
---
This work describes the adaptation of a pretrained sequence-to-sequence model
to the task of scientific claim verification in the biomedical domain. We
propose VERT5ERINI that exploits T5 for abstract retrieval, sentence selection
and label prediction, which are three critical sub-tasks of claim verification.
We evaluate our pipeline on SCIFACT, a newly curated dataset that requires
models to not just predict the veracity of claims but also provide relevant
sentences from a corpus of scientific literature that support this decision.
Empirically, our pipeline outperforms a strong baseline in each of the three
steps. Finally, we show VERT5ERINI's ability to generalize to two new datasets
of COVID-19 claims using evidence from the ever-expanding CORD-19 corpus.