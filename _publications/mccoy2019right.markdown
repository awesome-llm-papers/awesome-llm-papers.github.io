---
layout: publication
title: 'Right For The Wrong Reasons: Diagnosing Syntactic Heuristics In Natural Language
  Inference'
authors: R. Thomas Mccoy, Ellie Pavlick, Tal Linzen
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: mccoy2019right
citations: 945
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01007'}]
tags: ["Evaluation"]
short_authors: R. Thomas Mccoy, Ellie Pavlick, Tal Linzen
---
A machine learning system can score well on a given test set by relying on
heuristics that are effective for frequent example types but break down in more
challenging cases. We study this issue within natural language inference (NLI),
the task of determining whether one sentence entails another. We hypothesize
that statistical NLI models may adopt three fallible syntactic heuristics: the
lexical overlap heuristic, the subsequence heuristic, and the constituent
heuristic. To determine whether models have adopted these heuristics, we
introduce a controlled evaluation set called HANS (Heuristic Analysis for NLI
Systems), which contains many examples where the heuristics fail. We find that
models trained on MNLI, including BERT, a state-of-the-art model, perform very
poorly on HANS, suggesting that they have indeed adopted these heuristics. We
conclude that there is substantial room for improvement in NLI systems, and
that the HANS dataset can motivate and measure progress in this area