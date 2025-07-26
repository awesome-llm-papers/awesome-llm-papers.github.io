---
layout: publication
title: 'Qafacteval: Improved Qa-based Factual Consistency Evaluation For Summarization'
authors: Alexander R. Fabbri, Chien-sheng Wu, Wenhao Liu, Caiming Xiong
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
bibkey: fabbri2021qafacteval
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.08542'}]
tags: ["Evaluation", "NAACL"]
short_authors: Fabbri et al.
---
Factual consistency is an essential quality of text summarization models in
practical settings. Existing work in evaluating this dimension can be broadly
categorized into two lines of research, entailment-based and question answering
(QA)-based metrics, and different experimental setups often lead to contrasting
conclusions as to which paradigm performs the best. In this work, we conduct an
extensive comparison of entailment and QA-based metrics, demonstrating that
carefully choosing the components of a QA-based metric, especially question
generation and answerability classification, is critical to performance.
Building on those insights, we propose an optimized metric, which we call
QAFactEval, that leads to a 14% average improvement over previous QA-based
metrics on the SummaC factual consistency benchmark, and also outperforms the
best-performing entailment-based metric. Moreover, we find that QA-based and
entailment-based metrics can offer complementary signals and be combined into a
single metric for a further performance boost.