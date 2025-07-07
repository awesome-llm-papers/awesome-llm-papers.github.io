---
layout: publication
title: How Can We Know What Language Models Know?
authors: Zhengbao Jiang, Frank F. Xu, Jun Araki, Graham Neubig
conference: Arxiv
year: 2019
citations: 455
bibkey: jiang2019how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.12543'}, {name: Code,
    url: 'https://github.com/jzbjyb/LPAQA'}]
tags: [Has Code, Prompting]
---
Recent work has presented intriguing results examining the knowledge
contained in language models (LM) by having the LM fill in the blanks of
prompts such as "Obama is a _ by profession". These prompts are usually
manually created, and quite possibly sub-optimal; another prompt such as "Obama
worked as a _" may result in more accurately predicting the correct profession.
Because of this, given an inappropriate prompt, we might fail to retrieve facts
that the LM does know, and thus any given prompt only provides a lower bound
estimate of the knowledge contained in an LM. In this paper, we attempt to more
accurately estimate the knowledge contained in LMs by automatically discovering
better prompts to use in this querying process. Specifically, we propose
mining-based and paraphrasing-based methods to automatically generate
high-quality and diverse prompts, as well as ensemble methods to combine
answers from different prompts. Extensive experiments on the LAMA benchmark for
extracting relational knowledge from LMs demonstrate that our methods can
improve accuracy from 31.1% to 39.6%, providing a tighter lower bound on what
LMs know. We have released the code and the resulting LM Prompt And Query
Archive (LPAQA) at https://github.com/jzbjyb/LPAQA.