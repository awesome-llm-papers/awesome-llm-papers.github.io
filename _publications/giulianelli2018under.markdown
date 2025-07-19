---
layout: publication
title: 'Under The Hood: Using Diagnostic Classifiers To Investigate And Improve How
  Language Models Track Agreement Information'
authors: Giulianelli et al.
conference: 'Proceedings of the 2018 EMNLP Workshop BlackboxNLP: Analyzing and Interpreting
  Neural Networks for NLP'
year: 2018
bibkey: giulianelli2018under
citations: 195
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.08079'}]
tags: [Model Architecture, EMNLP]
---
How do neural language models keep track of number agreement between subject
and verb? We show that `diagnostic classifiers', trained to predict number from
the internal states of a language model, provide a detailed understanding of
how, when, and where this information is represented. Moreover, they give us
insight into when and where number information is corrupted in cases where the
language model ends up making agreement errors. To demonstrate the causal role
played by the representations we find, we then use agreement information to
influence the course of the LSTM during the processing of difficult sentences.
Results from such an intervention reveal a large increase in the language
model's accuracy. Together, these results show that diagnostic classifiers give
us an unrivalled detailed look into the representation of linguistic
information in neural models, and demonstrate that this knowledge can be used
to improve their performance.