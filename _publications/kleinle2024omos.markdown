---
layout: publication
title: 'Omos-qa: A Dataset For Cross-lingual Extractive Question Answering In A German
  Migration Context'
authors: Kleinle Steffen, Prange Jakob, Friedrich Annemarie
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: kleinle2024omos
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.15736'}]
tags: [Datasets, Reinforcement Learning, ACL]
---
When immigrating to a new country, it is easy to feel overwhelmed by the need
to obtain information on financial support, housing, schooling, language
courses, and other issues. If relocation is rushed or even forced, the
necessity for high-quality answers to such questions is all the more urgent.
Official immigration counselors are usually overbooked, and online systems
could guide newcomers to the requested information or a suitable counseling
service.
  To this end, we present OMoS-QA, a dataset of German and English questions
paired with relevant trustworthy documents and manually annotated answers,
specifically tailored to this scenario. Questions are automatically generated
with an open-source large language model (LLM) and answer sentences are
selected by crowd workers with high agreement. With our data, we conduct a
comparison of 5 pretrained LLMs on the task of extractive question answering
(QA) in German and English. Across all models and both languages, we find high
precision and low-to-mid recall in selecting answer sentences, which is a
favorable trade-off to avoid misleading users. This performance even holds up
when the question language does not match the document language. When it comes
to identifying unanswerable questions given a context, there are larger
differences between the two languages.