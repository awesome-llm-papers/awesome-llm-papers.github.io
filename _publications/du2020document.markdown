---
layout: publication
title: Document-level Event Role Filler Extraction Using Multi-granularity Contextualized
  Encoding
authors: Xinya Du, Claire Cardie
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: du2020document
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.06579'}]
tags: ["Memory & Context"]
short_authors: Xinya Du, Claire Cardie
---
Few works in the literature of event extraction have gone beyond individual
sentences to make extraction decisions. This is problematic when the
information needed to recognize an event argument is spread across multiple
sentences. We argue that document-level event extraction is a difficult task
since it requires a view of a larger context to determine which spans of text
correspond to event role fillers. We first investigate how end-to-end neural
sequence models (with pre-trained language model representations) perform on
document-level role filler extraction, as well as how the length of context
captured affects the models' performance. To dynamically aggregate information
captured by neural representations learned at different levels of granularity
(e.g., the sentence- and paragraph-level), we propose a novel multi-granularity
reader. We evaluate our models on the MUC-4 event extraction dataset, and show
that our best system performs substantially better than prior work. We also
report findings on the relationship between context length and neural model
performance on the task.