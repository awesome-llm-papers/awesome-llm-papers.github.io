---
layout: publication
title: Unsupervised Domain Clusters In Pretrained Language Models
authors: Roee Aharoni, Yoav Goldberg
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: aharoni2020unsupervised
citations: 174
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.02105'}]
tags: []
short_authors: Roee Aharoni, Yoav Goldberg
---
The notion of "in-domain data" in NLP is often over-simplistic and vague, as
textual data varies in many nuanced linguistic aspects such as topic, style or
level of formality. In addition, domain labels are many times unavailable,
making it challenging to build domain-specific systems. We show that massive
pre-trained language models implicitly learn sentence representations that
cluster by domains without supervision -- suggesting a simple data-driven
definition of domains in textual data. We harness this property and propose
domain data selection methods based on such models, which require only a small
set of in-domain monolingual data. We evaluate our data selection methods for
neural machine translation across five diverse domains, where they outperform
an established approach as measured by both BLEU and by precision and recall of
sentence selection with respect to an oracle.