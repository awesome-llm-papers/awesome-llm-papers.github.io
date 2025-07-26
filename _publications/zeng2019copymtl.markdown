---
layout: publication
title: 'Copymtl: Copy Mechanism For Joint Extraction Of Entities And Relations With
  Multi-task Learning'
authors: Daojian Zeng, Ranran Haoran Zhang, Qianying Liu
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: zeng2019copymtl
citations: 181
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.10438'}]
tags: ["AAAI", "Tools"]
short_authors: Daojian Zeng, Ranran Haoran Zhang, Qianying Liu
---
Joint extraction of entities and relations has received significant attention
due to its potential of providing higher performance for both tasks. Among
existing methods, CopyRE is effective and novel, which uses a
sequence-to-sequence framework and copy mechanism to directly generate the
relation triplets. However, it suffers from two fatal problems. The model is
extremely weak at differing the head and tail entity, resulting in inaccurate
entity extraction. It also cannot predict multi-token entities (e.g.
\textit\{Steven Jobs\}). To address these problems, we give a detailed analysis
of the reasons behind the inaccurate entity extraction problem, and then
propose a simple but extremely effective model structure to solve this problem.
In addition, we propose a multi-task learning framework equipped with copy
mechanism, called CopyMTL, to allow the model to predict multi-token entities.
Experiments reveal the problems of CopyRE and show that our model achieves
significant improvement over the current state-of-the-art method by 9% in NYT
and 16% in WebNLG (F1 score). Our code is available at
https://github.com/WindChimeRan/CopyMTL