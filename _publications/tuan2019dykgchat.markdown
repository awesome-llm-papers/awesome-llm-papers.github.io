---
layout: publication
title: 'Dykgchat: Benchmarking Dialogue Generation Grounding On Dynamic Knowledge
  Graphs'
authors: Yi-lin Tuan, Yun-nung Chen, Hung-yi Lee
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: tuan2019dykgchat
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.00610'}]
tags: ["Datasets", "EMNLP", "Evaluation"]
short_authors: Yi-lin Tuan, Yun-nung Chen, Hung-yi Lee
---
Data-driven, knowledge-grounded neural conversation models are capable of
generating more informative responses. However, these models have not yet
demonstrated that they can zero-shot adapt to updated, unseen knowledge graphs.
This paper proposes a new task about how to apply dynamic knowledge graphs in
neural conversation model and presents a novel TV series conversation corpus
(DyKgChat) for the task. Our new task and corpus aids in understanding the
influence of dynamic knowledge graphs on responses generation. Also, we propose
a preliminary model that selects an output from two networks at each time step:
a sequence-to-sequence model (Seq2Seq) and a multi-hop reasoning model, in
order to support dynamic knowledge graphs. To benchmark this new task and
evaluate the capability of adaptation, we introduce several evaluation metrics
and the experiments show that our proposed approach outperforms previous
knowledge-grounded conversation models. The proposed corpus and model can
motivate the future research directions.