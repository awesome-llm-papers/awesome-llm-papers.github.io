---
layout: publication
title: 'Hallucination Is Inevitable: An Innate Limitation Of Large Language Models'
authors: Ziwei Xu, Sanjay Jain, Mohan Kankanhalli
conference: Arxiv
year: 2024
bibkey: xu2024hallucination
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.11817'}]
tags: ["Tools"]
short_authors: Ziwei Xu, Sanjay Jain, Mohan Kankanhalli
---
Hallucination has been widely recognized to be a significant drawback for
large language models (LLMs). There have been many works that attempt to reduce
the extent of hallucination. These efforts have mostly been empirical so far,
which cannot answer the fundamental question whether it can be completely
eliminated. In this paper, we formalize the problem and show that it is
impossible to eliminate hallucination in LLMs. Specifically, we define a formal
world where hallucination is defined as inconsistencies between a computable
LLM and a computable ground truth function. By employing results from learning
theory, we show that LLMs cannot learn all the computable functions and will
therefore inevitably hallucinate if used as general problem solvers. Since the
formal world is a part of the real world which is much more complicated,
hallucinations are also inevitable for real world LLMs. Furthermore, for real
world LLMs constrained by provable time complexity, we describe the
hallucination-prone tasks and empirically validate our claims. Finally, using
the formal world framework, we discuss the possible mechanisms and efficacies
of existing hallucination mitigators as well as the practical implications on
the safe deployment of LLMs.