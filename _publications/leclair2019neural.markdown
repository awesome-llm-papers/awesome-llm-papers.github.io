---
layout: publication
title: A Neural Model For Generating Natural Language Summaries Of Program Subroutines
authors: Alexander Leclair, Siyuan Jiang, Collin Mcmillan
conference: 2019 IEEE/ACM 41st International Conference on Software Engineering (ICSE)
year: 2019
bibkey: leclair2019neural
citations: 280
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01954'}]
tags: ["Applications", "Llm For Code"]
short_authors: Alexander Leclair, Siyuan Jiang, Collin Mcmillan
---
Source code summarization -- creating natural language descriptions of source
code behavior -- is a rapidly-growing research topic with applications to
automatic documentation generation, program comprehension, and software
maintenance. Traditional techniques relied on heuristics and templates built
manually by human experts. Recently, data-driven approaches based on neural
machine translation have largely overtaken template-based systems. But nearly
all of these techniques rely almost entirely on programs having good internal
documentation; without clear identifier names, the models fail to create good
summaries. In this paper, we present a neural model that combines words from
code with code structure from an AST. Unlike previous approaches, our model
processes each data source as a separate input, which allows the model to learn
code structure independent of the text in code. This process helps our approach
provide coherent summaries in many cases even when zero internal documentation
is provided. We evaluate our technique with a dataset we created from 2.1m Java
methods. We find improvement over two baseline techniques from SE literature
and one from NLP literature.