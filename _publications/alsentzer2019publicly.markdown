---
layout: publication
title: Publicly Available Clinical BERT Embeddings
authors: Emily Alsentzer, John R. Murphy, Willie Boag, Wei-hung Weng, di Jin, Tristan
  Naumann, Matthew B. A. Mcdermott
conference: Arxiv
year: 2019
bibkey: alsentzer2019publicly
citations: 664
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.03323'}]
tags: ["Model Architecture"]
short_authors: Alsentzer et al.
---
Contextual word embedding models such as ELMo (Peters et al., 2018) and BERT
(Devlin et al., 2018) have dramatically improved performance for many natural
language processing (NLP) tasks in recent months. However, these models have
been minimally explored on specialty corpora, such as clinical text; moreover,
in the clinical domain, no publicly-available pre-trained BERT models yet
exist. In this work, we address this need by exploring and releasing BERT
models for clinical text: one for generic clinical text and another for
discharge summaries specifically. We demonstrate that using a domain-specific
model yields performance improvements on three common clinical NLP tasks as
compared to nonspecific embeddings. These domain-specific models are not as
performant on two clinical de-identification tasks, and argue that this is a
natural consequence of the differences between de-identified source text and
synthetically non de-identified task text.