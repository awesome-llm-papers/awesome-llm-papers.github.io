---
layout: publication
title: 'Evaluating Large Language Models On Graphs: Performance Insights And Comparative
  Analysis'
authors: Chang Liu, Bo Wu
conference: Arxiv
year: 2023
bibkey: liu2023evaluating
citations: 82
additional_links: [{name: Code, url: 'https://github.com/Ayame1006/LLMtoGraph'}, {
    name: Paper, url: 'https://arxiv.org/abs/2308.11224'}]
tags: ["Evaluation"]
short_authors: Chang Liu, Bo Wu
---
Large Language Models (LLMs) have garnered considerable interest within both
academic and industrial. Yet, the application of LLMs to graph data remains
under-explored. In this study, we evaluate the capabilities of four LLMs in
addressing several analytical problems with graph data. We employ four distinct
evaluation metrics: Comprehension, Correctness, Fidelity, and Rectification.
Our results show that: 1) LLMs effectively comprehend graph data in natural
language and reason with graph topology. 2) GPT models can generate logical and
coherent results, outperforming alternatives in correctness. 3) All examined
LLMs face challenges in structural reasoning, with techniques like zero-shot
chain-of-thought and few-shot prompting showing diminished efficacy. 4) GPT
models often produce erroneous answers in multi-answer tasks, raising concerns
in fidelity. 5) GPT models exhibit elevated confidence in their outputs,
potentially hindering their rectification capacities. Notably, GPT-4 has
demonstrated the capacity to rectify responses from GPT-3.5-turbo and its own
previous iterations. The code is available at:
https://github.com/Ayame1006/LLMtoGraph.