---
layout: publication
title: 'Sparc: Cross-domain Semantic Parsing In Context'
authors: Tao Yu, Rui Zhang, Michihiro Yasunaga, Yi Chern Tan, Xi Victoria Lin, Suyi
  Li, Heyang Er, Irene Li, Bo Pang, Tao Chen, Emily Ji, Shreya Dixit, David Proctor,
  Sungrok Shim, Jonathan Kraft, Vincent Zhang, Caiming Xiong, Richard Socher, Dragomir
  Radev
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: yu2019sparc
citations: 111
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.02285'}]
tags: ["Datasets", "Evaluation", "Has Code"]
short_authors: Yu et al.
---
We present SParC, a dataset for cross-domainSemanticParsing inContext that
consists of 4,298 coherent question sequences (12k+ individual questions
annotated with SQL queries). It is obtained from controlled user interactions
with 200 complex databases over 138 domains. We provide an in-depth analysis of
SParC and show that it introduces new challenges compared to existing datasets.
SParC demonstrates complex contextual dependencies, (2) has greater semantic
diversity, and (3) requires generalization to unseen domains due to its
cross-domain nature and the unseen databases at test time. We experiment with
two state-of-the-art text-to-SQL models adapted to the context-dependent,
cross-domain setup. The best model obtains an exact match accuracy of 20.2%
over all questions and less than10% over all interaction sequences, indicating
that the cross-domain setting and the con-textual phenomena of the dataset
present significant challenges for future research. The dataset, baselines, and
leaderboard are released at https://yale-lily.github.io/sparc.