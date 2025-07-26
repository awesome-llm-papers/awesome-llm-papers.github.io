---
layout: publication
title: Did Aristotle Use A Laptop? A Question Answering Benchmark With Implicit Reasoning
  Strategies
authors: Mor Geva, Daniel Khashabi, Elad Segal, Tushar Khot, Dan Roth, Jonathan Berant
conference: Arxiv
year: 2021
bibkey: geva2021did
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.02235'}]
tags: ["Datasets", "Evaluation"]
short_authors: Geva et al.
---
A key limitation in current datasets for multi-hop reasoning is that the
required steps for answering the question are mentioned in it explicitly. In
this work, we introduce StrategyQA, a question answering (QA) benchmark where
the required reasoning steps are implicit in the question, and should be
inferred using a strategy. A fundamental challenge in this setup is how to
elicit such creative questions from crowdsourcing workers, while covering a
broad range of potential strategies. We propose a data collection procedure
that combines term-based priming to inspire annotators, careful control over
the annotator population, and adversarial filtering for eliminating reasoning
shortcuts. Moreover, we annotate each question with (1) a decomposition into
reasoning steps for answering it, and (2) Wikipedia paragraphs that contain the
answers to each step. Overall, StrategyQA includes 2,780 examples, each
consisting of a strategy question, its decomposition, and evidence paragraphs.
Analysis shows that questions in StrategyQA are short, topic-diverse, and cover
a wide range of strategies. Empirically, we show that humans perform well (87%)
on this task, while our best baseline reaches an accuracy of \\(\sim\\)66%.