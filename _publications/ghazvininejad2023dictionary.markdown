---
layout: publication
title: Dictionary-based Phrase-level Prompting Of Large Language Models For Machine
  Translation
authors: Marjan Ghazvininejad, Hila Gonen, Luke Zettlemoyer
conference: Arxiv
year: 2023
citations: 23
bibkey: ghazvininejad2023dictionary
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.07856'}]
tags: [Prompting]
---
Large language models (LLMs) demonstrate remarkable machine translation (MT)
abilities via prompting, even though they were not explicitly trained for this
task. However, even given the incredible quantities of data they are trained
on, LLMs can struggle to translate inputs with rare words, which are common in
low resource or domain transfer scenarios. We show that LLM prompting can
provide an effective solution for rare words as well, by using prior knowledge
from bilingual dictionaries to provide control hints in the prompts. We propose
a novel method, DiPMT, that provides a set of possible translations for a
subset of the input words, thereby enabling fine-grained phrase-level prompted
control of the LLM. Extensive experiments show that DiPMT outperforms the
baseline both in low-resource MT, as well as for out-of-domain MT. We further
provide a qualitative analysis of the benefits and limitations of this
approach, including the overall level of controllability that is achieved.