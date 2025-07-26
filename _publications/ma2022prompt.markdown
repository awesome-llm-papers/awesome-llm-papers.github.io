---
layout: publication
title: 'Prompt For Extraction? PAIE: Prompting Argument Interaction For Event Argument
  Extraction'
authors: Yubo Ma, Zehao Wang, Yixin Cao, Mukai Li, Meiqi Chen, Kun Wang, Jing Shao
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: ma2022prompt
citations: 84
additional_links: [{name: Code, url: 'https://github.com/mayubo2333/PAIE'}, {name: Paper,
    url: 'https://arxiv.org/abs/2202.12109'}]
tags: ["Prompting"]
short_authors: Ma et al.
---
In this paper, we propose an effective yet efficient model PAIE for both
sentence-level and document-level Event Argument Extraction (EAE), which also
generalizes well when there is a lack of training data. On the one hand, PAIE
utilizes prompt tuning for extractive objectives to take the best advantages of
Pre-trained Language Models (PLMs). It introduces two span selectors based on
the prompt to select start/end tokens among input texts for each role. On the
other hand, it captures argument interactions via multi-role prompts and
conducts joint optimization with optimal span assignments via a bipartite
matching loss. Also, with a flexible prompt design, PAIE can extract multiple
arguments with the same role instead of conventional heuristic threshold
tuning. We have conducted extensive experiments on three benchmarks, including
both sentence- and document-level EAE. The results present promising
improvements from PAIE (3.5% and 2.3% F1 gains in average on three
benchmarks, for PAIE-base and PAIE-large respectively). Further analysis
demonstrates the efficiency, generalization to few-shot settings, and
effectiveness of different extractive prompt tuning strategies. Our code is
available at https://github.com/mayubo2333/PAIE.