---
layout: publication
title: 'Answering While Summarizing: Multi-task Learning For Multi-hop QA With Evidence
  Extraction'
authors: Kosuke Nishida, Kyosuke Nishida, Masaaki Nagata, Atsushi Otsuka, Itsumi Saito,
  Hisako Asano, Junji Tomita
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: nishida2019answering
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.08511'}]
tags: ["Model Architecture"]
short_authors: Nishida et al.
---
Question answering (QA) using textual sources for purposes such as reading
comprehension (RC) has attracted much attention. This study focuses on the task
of explainable multi-hop QA, which requires the system to return the answer
with evidence sentences by reasoning and gathering disjoint pieces of the
reference texts. It proposes the Query Focused Extractor (QFE) model for
evidence extraction and uses multi-task learning with the QA model. QFE is
inspired by extractive summarization models; compared with the existing method,
which extracts each evidence sentence independently, it sequentially extracts
evidence sentences by using an RNN with an attention mechanism on the question
sentence. It enables QFE to consider the dependency among the evidence
sentences and cover important information in the question sentence.
Experimental results show that QFE with a simple RC baseline model achieves a
state-of-the-art evidence extraction score on HotpotQA. Although designed for
RC, it also achieves a state-of-the-art evidence extraction score on FEVER,
which is a recognizing textual entailment task on a large textual database.