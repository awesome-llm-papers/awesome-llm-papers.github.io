---
layout: publication
title: A Simple And Effective Model For Answering Multi-span Questions
authors: Elad Segal, Avia Efrat, Mor Shoham, Amir Globerson, Jonathan Berant
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: segal2019simple
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.13375'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Segal et al.
---
Models for reading comprehension (RC) commonly restrict their output space to
the set of all single contiguous spans from the input, in order to alleviate
the learning problem and avoid the need for a model that generates text
explicitly. However, forcing an answer to be a single span can be restrictive,
and some recent datasets also include multi-span questions, i.e., questions
whose answer is a set of non-contiguous spans in the text. Naturally, models
that return single spans cannot answer these questions. In this work, we
propose a simple architecture for answering multi-span questions by casting the
task as a sequence tagging problem, namely, predicting for each input token
whether it should be part of the output or not. Our model substantially
improves performance on span extraction questions from DROP and Quoref by 9.9
and 5.5 EM points respectively.