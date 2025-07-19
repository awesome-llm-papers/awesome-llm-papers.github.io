---
layout: publication
title: Amr-to-text Generation With Synchronous Node Replacement Grammar
authors: Song et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2017
bibkey: song2017amr
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.00500'}]
tags: [ACL, Language Modeling, RAG, Training Techniques]
---
This paper addresses the task of AMR-to-text generation by leveraging
synchronous node replacement grammar. During training, graph-to-string rules
are learned using a heuristic extraction algorithm. At test time, a graph
transducer is applied to collapse input AMRs and generate output sentences.
Evaluated on SemEval-2016 Task 8, our method gives a BLEU score of 25.62, which
is the best reported so far.