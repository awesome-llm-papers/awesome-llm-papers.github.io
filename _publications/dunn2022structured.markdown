---
layout: publication
title: Structured Information Extraction From Complex Scientific Text With Fine-tuned
  Large Language Models
authors: Dunn et al.
conference: Nature Communications
year: 2022
bibkey: dunn2022structured
citations: 215
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.05238'}]
tags: [RAG, GPT, Prompting, Tools, Model Architecture, Reinforcement Learning]
---
Intelligently extracting and linking complex scientific information from
unstructured text is a challenging endeavor particularly for those
inexperienced with natural language processing. Here, we present a simple
sequence-to-sequence approach to joint named entity recognition and relation
extraction for complex hierarchical information in scientific text. The
approach leverages a pre-trained large language model (LLM), GPT-3, that is
fine-tuned on approximately 500 pairs of prompts (inputs) and completions
(outputs). Information is extracted either from single sentences or across
sentences in abstracts/passages, and the output can be returned as simple
English sentences or a more structured format, such as a list of JSON objects.
We demonstrate that LLMs trained in this way are capable of accurately
extracting useful records of complex scientific knowledge for three
representative tasks in materials chemistry: linking dopants with their host
materials, cataloging metal-organic frameworks, and general
chemistry/phase/morphology/application information extraction. This approach
represents a simple, accessible, and highly-flexible route to obtaining large
databases of structured knowledge extracted from unstructured text. An online
demo is available at http://www.matscholar.com/info-extraction.