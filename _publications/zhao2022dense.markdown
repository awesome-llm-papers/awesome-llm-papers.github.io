---
layout: publication
title: 'Dense Text Retrieval Based On Pretrained Language Models: A Survey'
authors: Wayne Xin Zhao, Jing Liu, Ruiyang Ren, Ji-rong Wen
conference: ACM Transactions on Information Systems
year: 2023
bibkey: zhao2022dense
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.14876'}]
tags: ["Survey Paper"]
short_authors: Zhao et al.
---
Text retrieval is a long-standing research topic on information seeking,
where a system is required to return relevant information resources to user's
queries in natural language. From classic retrieval methods to learning-based
ranking functions, the underlying retrieval models have been continually
evolved with the ever-lasting technical innovation. To design effective
retrieval models, a key point lies in how to learn the text representation and
model the relevance matching. The recent success of pretrained language models
(PLMs) sheds light on developing more capable text retrieval approaches by
leveraging the excellent modeling capacity of PLMs. With powerful PLMs, we can
effectively learn the representations of queries and texts in the latent
representation space, and further construct the semantic matching function
between the dense vectors for relevance modeling. Such a retrieval approach is
referred to as dense retrieval, since it employs dense vectors (a.k.a.,
embeddings) to represent the texts. Considering the rapid progress on dense
retrieval, in this survey, we systematically review the recent advances on
PLM-based dense retrieval. Different from previous surveys on dense retrieval,
we take a new perspective to organize the related work by four major aspects,
including architecture, training, indexing and integration, and summarize the
mainstream techniques for each aspect. We thoroughly survey the literature, and
include 300+ related reference papers on dense retrieval. To support our
survey, we create a website for providing useful resources, and release a code
repertory and toolkit for implementing dense retrieval models. This survey aims
to provide a comprehensive, practical reference focused on the major progress
for dense text retrieval.