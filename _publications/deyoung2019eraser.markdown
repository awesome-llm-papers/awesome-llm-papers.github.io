---
layout: publication
title: 'ERASER: A Benchmark To Evaluate Rationalized NLP Models'
authors: Jay Deyoung, Sarthak Jain, Nazneen Fatema Rajani, Eric Lehman, Caiming Xiong,
  Richard Socher, Byron C. Wallace
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: deyoung2019eraser
citations: 447
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03429'}]
tags: ["Evaluation"]
short_authors: Deyoung et al.
---
State-of-the-art models in NLP are now predominantly based on deep neural
networks that are opaque in terms of how they come to make predictions. This
limitation has increased interest in designing more interpretable deep models
for NLP that reveal the `reasoning' behind model outputs. But work in this
direction has been conducted on different datasets and tasks with
correspondingly unique aims and metrics; this makes it difficult to track
progress. We propose the Evaluating Rationales And Simple English Reasoning
(ERASER) benchmark to advance research on interpretable models in NLP. This
benchmark comprises multiple datasets and tasks for which human annotations of
"rationales" (supporting evidence) have been collected. We propose several
metrics that aim to capture how well the rationales provided by models align
with human rationales, and also how faithful these rationales are (i.e., the
degree to which provided rationales influenced the corresponding predictions).
Our hope is that releasing this benchmark facilitates progress on designing
more interpretable NLP systems. The benchmark, code, and documentation are
available at https://www.eraserbenchmark.com/