---
layout: publication
title: Multi-task Learning For Conversational Question Answering Over A Large-scale
  Knowledge Base
authors: Tao Shen, Xiubo Geng, Tao Qin, Daya Guo, Duyu Tang, Nan Duan, Guodong Long,
  Daxin Jiang
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: shen2019multi
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.05069'}]
tags: ["Datasets", "EMNLP"]
short_authors: Shen et al.
---
We consider the problem of conversational question answering over a
large-scale knowledge base. To handle huge entity vocabulary of a large-scale
knowledge base, recent neural semantic parsing based approaches usually
decompose the task into several subtasks and then solve them sequentially,
which leads to following issues: 1) errors in earlier subtasks will be
propagated and negatively affect downstream ones; and 2) each subtask cannot
naturally share supervision signals with others. To tackle these issues, we
propose an innovative multi-task learning framework where a pointer-equipped
semantic parsing model is designed to resolve coreference in conversations, and
naturally empower joint learning with a novel type-aware entity detection
model. The proposed framework thus enables shared supervisions and alleviates
the effect of error propagation. Experiments on a large-scale conversational
question answering dataset containing 1.6M question answering pairs over 12.8M
entities show that the proposed framework improves overall F1 score from 67% to
79% compared with previous state-of-the-art work.