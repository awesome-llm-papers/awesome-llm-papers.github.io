---
layout: publication
title: 'Citeme: Can Language Models Accurately Cite Scientific Claims?'
authors: Press et al.
conference: Proceedings of the 47th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2024
bibkey: press2024citeme
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.12861'}]
tags: [GPT, Agentic, Evaluation, Model Architecture, Reinforcement Learning, SIGIR,
  Datasets]
---
Thousands of new scientific papers are published each month. Such information
overload complicates researcher efforts to stay current with the
state-of-the-art as well as to verify and correctly attribute claims. We pose
the following research question: Given a text excerpt referencing a paper,
could an LM act as a research assistant to correctly identify the referenced
paper? We advance efforts to answer this question by building a benchmark that
evaluates the abilities of LMs in citation attribution. Our benchmark, CiteME,
consists of text excerpts from recent machine learning papers, each referencing
a single other paper. CiteME use reveals a large gap between frontier LMs and
human performance, with LMs achieving only 4.2-18.5% accuracy and humans 69.7%.
We close this gap by introducing CiteAgent, an autonomous system built on the
GPT-4o LM that can also search and read papers, which achieves an accuracy of
35.3% on CiteME. Overall, CiteME serves as a challenging testbed for
open-ended claim attribution, driving the research community towards a future
where any claim made by an LM can be automatically verified and discarded if
found to be incorrect.