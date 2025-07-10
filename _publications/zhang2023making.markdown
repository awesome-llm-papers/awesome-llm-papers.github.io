---
layout: publication
title: Making Large Language Models Perform Better In Knowledge Graph Completion
authors: Yichi Zhang et al.
conference: 'MM ''24: The 32nd ACM International Conference on Multimedia'
year: 2023
citations: 21
bibkey: zhang2023making
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.06671'}, {name: Code,
    url: 'https://github.com/zjukg/KoPA'}]
tags: [Has Code, Reinforcement Learning, In-Context Learning, Multimodal Models, Prompting,
  Pre-Training, Training Techniques]
---
Large language model (LLM) based knowledge graph completion (KGC) aims to
predict the missing triples in the KGs with LLMs. However, research about
LLM-based KGC fails to sufficiently harness LLMs' inference proficiencies,
overlooking critical structural information integral to KGs. In this paper, we
explore methods to incorporate structural information into the LLMs, with the
overarching goal of facilitating structure-aware reasoning. We first discuss on
the existing LLM paradigms like in-context learning and instruction tuning,
proposing basic structural information injection approaches. Then we propose a
Knowledge Prefix Adapter (KoPA) to fulfill this stated goal. The KoPA uses a
structural pre-training phase to comprehend the intricate entities and
relations within KGs, representing them as structural embeddings. Then KoPA
communicates such cross-modal structural information understanding to the LLMs
through a knowledge prefix adapter which projects the structural embeddings
into the textual space and obtains virtual knowledge tokens positioned as a
prefix of the input prompt. We conduct comprehensive experiments and provide
incisive analysis concerning how the introduction of cross-modal structural
information would be better for LLM's factual knowledge reasoning ability. Our
code and data are available at https://github.com/zjukg/KoPA .