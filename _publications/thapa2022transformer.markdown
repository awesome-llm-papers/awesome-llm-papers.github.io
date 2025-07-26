---
layout: publication
title: Transformer-based Language Models For Software Vulnerability Detection
authors: Chandra Thapa, Seung Ick Jang, Muhammad Ejaz Ahmed, Seyit Camtepe, Josef
  Pieprzyk, Surya Nepal
conference: Proceedings of the 38th Annual Computer Security Applications Conference
year: 2022
bibkey: thapa2022transformer
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.03214'}]
tags: ["Llm For Code", "Model Architecture", "Security", "Tools"]
short_authors: Thapa et al.
---
The large transformer-based language models demonstrate excellent performance
in natural language processing. By considering the transferability of the
knowledge gained by these models in one domain to other related domains, and
the closeness of natural languages to high-level programming languages, such as
C/C++, this work studies how to leverage (large) transformer-based language
models in detecting software vulnerabilities and how good are these models for
vulnerability detection tasks. In this regard, firstly, a systematic (cohesive)
framework that details source code translation, model preparation, and
inference is presented. Then, an empirical analysis is performed with software
vulnerability datasets with C/C++ source codes having multiple vulnerabilities
corresponding to the library function call, pointer usage, array usage, and
arithmetic expression. Our empirical results demonstrate the good performance
of the language models in vulnerability detection. Moreover, these language
models have better performance metrics, such as F1-score, than the contemporary
models, namely bidirectional long short-term memory and bidirectional gated
recurrent unit. Experimenting with the language models is always challenging
due to the requirement of computing resources, platforms, libraries, and
dependencies. Thus, this paper also analyses the popular platforms to
efficiently fine-tune these models and present recommendations while choosing
the platforms.