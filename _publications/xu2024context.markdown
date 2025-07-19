---
layout: publication
title: Context Graph
authors: Xu et al.
conference: Arxiv
year: 2024
bibkey: xu2024context
citations: 550
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.11160'}]
tags: [RAG, Reinforcement Learning, Applications]
---
Knowledge Graphs (KGs) are foundational structures in many AI applications,
representing entities and their interrelations through triples. However,
triple-based KGs lack the contextual information of relational knowledge, like
temporal dynamics and provenance details, which are crucial for comprehensive
knowledge representation and effective reasoning. Instead, \textbf\{Context
Graphs\} (CGs) expand upon the conventional structure by incorporating
additional information such as time validity, geographic location, and source
provenance. This integration provides a more nuanced and accurate understanding
of knowledge, enabling KGs to offer richer insights and support more
sophisticated reasoning processes. In this work, we first discuss the inherent
limitations of triple-based KGs and introduce the concept of CGs, highlighting
their advantages in knowledge representation and reasoning. We then present a
context graph reasoning \textbf\{CGR\\(^3\\)\} paradigm that leverages large language
models (LLMs) to retrieve candidate entities and related contexts, rank them
based on the retrieved information, and reason whether sufficient information
has been obtained to answer a query. Our experimental results demonstrate that
CGR\\(^3\\) significantly improves performance on KG completion (KGC) and KG
question answering (KGQA) tasks, validating the effectiveness of incorporating
contextual information on KG representation and reasoning.