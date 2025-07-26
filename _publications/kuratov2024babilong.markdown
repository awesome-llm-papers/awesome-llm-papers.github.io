---
layout: publication
title: 'Babilong: Testing The Limits Of Llms With Long Context Reasoning-in-a-haystack'
authors: Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Ivan Rodkin, Dmitry Sorokin, Artyom
  Sorokin, Mikhail Burtsev
conference: No Venue
year: 2024
bibkey: kuratov2024babilong
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.10149'}]
tags: ["Evaluation", "Memory & Context"]
short_authors: Kuratov et al.
---
In recent years, the input context sizes of large language models (LLMs) have increased dramatically. However, existing evaluation methods have not kept pace, failing to comprehensively assess the efficiency of models in handling long contexts. To bridge this gap, we introduce the BABILong benchmark, designed to test language models' ability to reason across facts distributed in extremely long documents. BABILong includes a diverse set of 20 reasoning tasks, including fact chaining, simple induction, deduction, counting, and handling lists/sets. These tasks are challenging on their own, and even more demanding when the required facts are scattered across long natural text. Our evaluations show that popular LLMs effectively utilize only 10-20% of the context and their performance declines sharply with increased reasoning complexity. Among alternatives to in-context reasoning, Retrieval-Augmented Generation methods achieve a modest 60% accuracy on single-fact question answering, independent of context length. Among context extension methods, the highest performance is demonstrated by recurrent memory transformers, enabling the processing of lengths up to 11 million tokens. The BABILong benchmark is extendable to any length to support the evaluation of new upcoming models with increased capabilities, and we provide splits up to 1 million token lengths.

https://huggingface.co/discussions/paper/666ffb682b9e452739047b19