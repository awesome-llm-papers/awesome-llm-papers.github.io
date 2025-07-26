---
layout: publication
title: 'Searchqa: A New Q&A Dataset Augmented With Context From A Search Engine'
authors: Matthew Dunn, Levent Sagun, Mike Higgins, V. Ugur Guney, Volkan Cirik, Kyunghyun
  Cho
conference: Arxiv
year: 2017
bibkey: dunn2017searchqa
citations: 423
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.05179'}]
tags: ["Datasets"]
short_authors: Dunn et al.
---
We publicly release a new large-scale dataset, called SearchQA, for machine
comprehension, or question-answering. Unlike recently released datasets, such
as DeepMind CNN/DailyMail and SQuAD, the proposed SearchQA was constructed to
reflect a full pipeline of general question-answering. That is, we start not
from an existing article and generate a question-answer pair, but start from an
existing question-answer pair, crawled from J! Archive, and augment it with
text snippets retrieved by Google. Following this approach, we built SearchQA,
which consists of more than 140k question-answer pairs with each pair having
49.6 snippets on average. Each question-answer-context tuple of the SearchQA
comes with additional meta-data such as the snippet's URL, which we believe
will be valuable resources for future research. We conduct human evaluation as
well as test two baseline methods, one simple word selection and the other deep
learning based, on the SearchQA. We show that there is a meaningful gap between
the human and machine performances. This suggests that the proposed dataset
could well serve as a benchmark for question-answering.