---
layout: publication
title: What Does It Mean For A Language Model To Preserve Privacy?
authors: Brown et al.
conference: 2022 ACM Conference on Fairness Accountability and Transparency
year: 2022
bibkey: brown2022what
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.05520'}]
tags: [Ethics And Bias, Training Techniques, Fairness, Ethics and Bias, Bias Mitigation,
  Responsible AI]
---
Natural language reflects our private lives and identities, making its
privacy concerns as broad as those of real life. Language models lack the
ability to understand the context and sensitivity of text, and tend to memorize
phrases present in their training sets. An adversary can exploit this tendency
to extract training data. Depending on the nature of the content and the
context in which this data was collected, this could violate expectations of
privacy. Thus there is a growing interest in techniques for training language
models that preserve privacy. In this paper, we discuss the mismatch between
the narrow assumptions made by popular data protection techniques (data
sanitization and differential privacy), and the broadness of natural language
and of privacy as a social norm. We argue that existing protection methods
cannot guarantee a generic and meaningful notion of privacy for language
models. We conclude that language models should be trained on text data which
was explicitly produced for public use.