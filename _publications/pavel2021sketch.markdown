---
layout: publication
title: A Sketch-based Neural Model For Generating Commit Messages From Diffs
authors: Pavel Nicolae-teodor, Rebedea Traian
conference: 2017 32nd IEEE/ACM International Conference on Automated Software Engineering
  (ASE)
year: 2021
bibkey: pavel2021sketch
citations: 156
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.04087'}]
tags: [Datasets, LLM for Code, Training Techniques, LLM For Code]
---
Commit messages have an important impact in software development, especially
when working in large teams. Multiple developers who have a different style of
writing may often be involved in the same project. For this reason, it may be
difficult to maintain a strict pattern of writing informative commit messages,
with the most frequent issue being that these messages are not descriptive
enough. In this paper we apply neural machine translation (NMT) techniques to
convert code diffs into commit messages and we present an improved sketch-based
encoder for this task. We split the approach into three parts. Firstly, we
focus on finding a more suitable NMT baseline for this problem. Secondly, we
show that the performance of the NMT models can be improved by training on
examples containing a specific file type. Lastly, we introduce a novel
sketch-based neural model inspired by recent approaches used for code
generation and we show that the sketch-based encoder significantly outperforms
existing state of the art solutions. The results highlight that this
improvement is relevant especially for Java source code files, by examining two
different datasets introduced in recent years for this task.