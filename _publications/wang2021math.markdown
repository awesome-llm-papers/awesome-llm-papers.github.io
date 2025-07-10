---
layout: publication
title: Math Word Problem Generation With Mathematical Consistency And Problem Context
  Constraints
authors: Zichao Wang, Andrew S. Lan, Richard G. Baraniuk
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
citations: 19
bibkey: wang2021math
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04546'}]
tags: [Reinforcement Learning, RAG]
---
We study the problem of generating arithmetic math word problems (MWPs) given
a math equation that specifies the mathematical computation and a context that
specifies the problem scenario. Existing approaches are prone to generating
MWPs that are either mathematically invalid or have unsatisfactory language
quality. They also either ignore the context or require manual specification of
a problem template, which compromises the diversity of the generated MWPs. In
this paper, we develop a novel MWP generation approach that leverages i)
pre-trained language models and a context keyword selection model to improve
the language quality of the generated MWPs and ii) an equation consistency
constraint for math equations to improve the mathematical validity of the
generated MWPs. Extensive quantitative and qualitative experiments on three
real-world MWP datasets demonstrate the superior performance of our approach
compared to various baselines.