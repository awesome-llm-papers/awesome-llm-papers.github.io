---
layout: publication
title: Generating Wikipedia By Summarizing Long Sequences
authors: Peter J. Liu, Mohammad Saleh, Etienne Pot, Ben Goodrich, Ryan Sepassi, Lukasz
  Kaiser, Noam Shazeer
conference: Arxiv
year: 2018
bibkey: liu2018generating
citations: 549
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.10198'}]
tags: ["Model Architecture"]
short_authors: Liu et al.
---
We show that generating English Wikipedia articles can be approached as a
multi- document summarization of source documents. We use extractive
summarization to coarsely identify salient information and a neural abstractive
model to generate the article. For the abstractive model, we introduce a
decoder-only architecture that can scalably attend to very long sequences, much
longer than typical encoder- decoder architectures used in sequence
transduction. We show that this model can generate fluent, coherent
multi-sentence paragraphs and even whole Wikipedia articles. When given
reference documents, we show it can extract relevant factual information as
reflected in perplexity, ROUGE scores and human evaluations.