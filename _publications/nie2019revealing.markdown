---
layout: publication
title: Revealing The Importance Of Semantic Retrieval For Machine Reading At Scale
authors: Yixin Nie, Songhe Wang, Mohit Bansal
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: nie2019revealing
citations: 152
additional_links: [{name: Code, url: 'https://github.com/easonnie/semanticRetrievalMRS'},
  {name: Paper, url: 'https://arxiv.org/abs/1909.08041'}]
tags: ["EMNLP"]
short_authors: Yixin Nie, Songhe Wang, Mohit Bansal
---
Machine Reading at Scale (MRS) is a challenging task in which a system is
given an input query and is asked to produce a precise output by "reading"
information from a large knowledge base. The task has gained popularity with
its natural combination of information retrieval (IR) and machine comprehension
(MC). Advancements in representation learning have led to separated progress in
both IR and MC; however, very few studies have examined the relationship and
combined design of retrieval and comprehension at different levels of
granularity, for development of MRS systems. In this work, we give general
guidelines on system design for MRS by proposing a simple yet effective
pipeline system with special consideration on hierarchical semantic retrieval
at both paragraph and sentence level, and their potential effects on the
downstream task. The system is evaluated on both fact verification and
open-domain multihop QA, achieving state-of-the-art results on the leaderboard
test sets of both FEVER and HOTPOTQA. To further demonstrate the importance of
semantic retrieval, we present ablation and analysis studies to quantify the
contribution of neural retrieval modules at both paragraph-level and
sentence-level, and illustrate that intermediate semantic retrieval modules are
vital for not only effectively filtering upstream information and thus saving
downstream computation, but also for shaping upstream data distribution and
providing better data for downstream modeling. Code/data made publicly
available at: https://github.com/easonnie/semanticRetrievalMRS