---
layout: publication
title: 'Visconde: Multi-document QA With GPT-3 And Neural Reranking'
authors: Jayr Pereira, Robson Fidalgo, Roberto Lotufo, Rodrigo Nogueira
conference: Lecture Notes in Computer Science
year: 2022
citations: 17
bibkey: pereira2022multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.09656'}, {name: Code,
    url: 'https://github.com/neuralmind-ai/visconde'}]
tags: [Has Code, Model Architecture, Few-Shot, Interpretability and Explainability,
  Reinforcement Learning, GPT]
---
This paper proposes a question-answering system that can answer questions
whose supporting evidence is spread over multiple (potentially long) documents.
The system, called Visconde, uses a three-step pipeline to perform the task:
decompose, retrieve, and aggregate. The first step decomposes the question into
simpler questions using a few-shot large language model (LLM). Then, a
state-of-the-art search engine is used to retrieve candidate passages from a
large collection for each decomposed question. In the final step, we use the
LLM in a few-shot setting to aggregate the contents of the passages into the
final answer. The system is evaluated on three datasets: IIRC, Qasper, and
StrategyQA. Results suggest that current retrievers are the main bottleneck and
that readers are already performing at the human level as long as relevant
passages are provided. The system is also shown to be more effective when the
model is induced to give explanations before answering a question. Code is
available at https://github.com/neuralmind-ai/visconde.