---
layout: publication
title: Measuring And Improving Consistency In Pretrained Language Models
authors: "Yanai Elazar, Nora Kassner, Shauli Ravfogel, Abhilasha Ravichander, Eduard\
  \ Hovy, Hinrich Sch\xFCtze, Yoav Goldberg"
conference: Transactions of the Association for Computational Linguistics
year: 2021
bibkey: elazar2021measuring
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.01017'}]
tags: ["TACL"]
short_authors: Elazar et al.
---
Consistency of a model -- that is, the invariance of its behavior under
meaning-preserving alternations in its input -- is a highly desirable property
in natural language processing. In this paper we study the question: Are
Pretrained Language Models (PLMs) consistent with respect to factual knowledge?
To this end, we create ParaRel, a high-quality resource of cloze-style query
English paraphrases. It contains a total of 328 paraphrases for 38 relations.
Using ParaRel, we show that the consistency of all PLMs we experiment with is
poor -- though with high variance between relations. Our analysis of the
representational spaces of PLMs suggests that they have a poor structure and
are currently not suitable for representing knowledge robustly. Finally, we
propose a method for improving model consistency and experimentally demonstrate
its effectiveness.