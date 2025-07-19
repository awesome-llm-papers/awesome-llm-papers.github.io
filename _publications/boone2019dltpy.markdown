---
layout: publication
title: 'Dltpy: Deep Learning Type Inference Of Python Function Signatures Using Natural
  Language Context'
authors: Boone et al.
conference: Proceedings of the 2016 24th ACM SIGSOFT International Symposium on Foundations
  of Software Engineering
year: 2019
bibkey: boone2019dltpy
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.00680'}]
tags: [LLM for Code, LLM For Code]
---
Due to the rise of machine learning, Python is an increasingly popular
programming language. Python, however, is dynamically typed. Dynamic typing has
shown to have drawbacks when a project grows, while at the same time it
improves developer productivity. To have the benefits of static typing,
combined with high developer productivity, types need to be inferred. In this
paper, we present DLTPy: a deep learning type inference solution for the
prediction of types in function signatures based on the natural language
context (identifier names, comments and return expressions) of a function. We
found that DLTPy is effective and has a top-3 F1-score of 91.6%. This means
that in most of the cases the correct type is within the top-3 predictions. We
conclude that natural language contained in comments and return expressions are
beneficial to predicting types more accurately. DLTPy does not significantly
outperform or underperform the previous work NL2Type for Javascript, but does
show that similar prediction is possible for Python.