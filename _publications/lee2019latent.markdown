---
layout: publication
title: Latent Retrieval For Weakly Supervised Open Domain Question Answering
authors: Kenton Lee, Ming-wei Chang, Kristina Toutanova
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: lee2019latent
citations: 709
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00300'}]
tags: ["Datasets", "Retrieval Systems"]
short_authors: Kenton Lee, Ming-wei Chang, Kristina Toutanova
---
Recent work on open domain question answering (QA) assumes strong supervision
of the supporting evidence and/or assumes a blackbox information retrieval (IR)
system to retrieve evidence candidates. We argue that both are suboptimal,
since gold evidence is not always available, and QA is fundamentally different
from IR. We show for the first time that it is possible to jointly learn the
retriever and reader from question-answer string pairs and without any IR
system. In this setting, evidence retrieval from all of Wikipedia is treated as
a latent variable. Since this is impractical to learn from scratch, we
pre-train the retriever with an Inverse Cloze Task. We evaluate on open
versions of five QA datasets. On datasets where the questioner already knows
the answer, a traditional IR system such as BM25 is sufficient. On datasets
where a user is genuinely seeking an answer, we show that learned retrieval is
crucial, outperforming BM25 by up to 19 points in exact match.