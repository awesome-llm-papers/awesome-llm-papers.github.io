---
layout: publication
title: 'CURE: Code-aware Neural Machine Translation For Automatic Program Repair'
authors: Nan Jiang, Thibaud Lutellier, Lin Tan
conference: 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE)
year: 2021
bibkey: jiang2021cure
citations: 204
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.00073'}]
tags: ["Llm For Code"]
short_authors: Nan Jiang, Thibaud Lutellier, Lin Tan
---
Automatic program repair (APR) is crucial to improve software reliability.
Recently, neural machine translation (NMT) techniques have been used to fix
software bugs automatically. While promising, these approaches have two major
limitations. Their search space often does not contain the correct fix, and
their search strategy ignores software knowledge such as strict code syntax.
Due to these limitations, existing NMT-based techniques underperform the best
template-based approaches.
  We propose CURE, a new NMT-based APR technique with three major novelties.
First, CURE pre-trains a programming language (PL) model on a large software
codebase to learn developer-like source code before the APR task. Second, CURE
designs a new code-aware search strategy that finds more correct fixes by
focusing on compilable patches and patches that are close in length to the
buggy code. Finally, CURE uses a subword tokenization technique to generate a
smaller search space that contains more correct fixes.
  Our evaluation on two widely-used benchmarks shows that CURE correctly fixes
57 Defects4J bugs and 26 QuixBugs bugs, outperforming all existing APR
techniques on both benchmarks.