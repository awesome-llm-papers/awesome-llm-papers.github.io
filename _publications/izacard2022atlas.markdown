---
layout: publication
title: 'Atlas: Few-shot Learning With Retrieval Augmented Language Models'
authors: Gautier Izacard, Patrick Lewis, Maria Lomeli, Lucas Hosseini, Fabio Petroni,
  Timo Schick, Jane Dwivedi-yu, Armand Joulin, Sebastian Riedel, Edouard Grave
conference: Arxiv
year: 2022
bibkey: izacard2022atlas
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.03299'}]
tags: ["Few-Shot"]
short_authors: Izacard et al.
---
Large language models have shown impressive few-shot results on a wide range
of tasks. However, when knowledge is key for such results, as is the case for
tasks such as question answering and fact checking, massive parameter counts to
store knowledge seem to be needed. Retrieval augmented models are known to
excel at knowledge intensive tasks without the need for as many parameters, but
it is unclear whether they work in few-shot settings. In this work we present
Atlas, a carefully designed and pre-trained retrieval augmented language model
able to learn knowledge intensive tasks with very few training examples. We
perform evaluations on a wide range of tasks, including MMLU, KILT and
NaturalQuestions, and study the impact of the content of the document index,
showing that it can easily be updated. Notably, Atlas reaches over 42% accuracy
on Natural Questions using only 64 examples, outperforming a 540B parameters
model by 3% despite having 50x fewer parameters.