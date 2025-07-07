---
layout: publication
title: 'Ragas: Automated Evaluation Of Retrieval Augmented Generation'
authors: Shahul Es, Jithin James, Luis Espinosa-anke, Steven Schockaert
conference: Arxiv
year: 2023
citations: 33
bibkey: es2023automated
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.15217'}]
tags: [RAG, Tools, Model Architecture]
---
We introduce Ragas (Retrieval Augmented Generation Assessment), a framework
for reference-free evaluation of Retrieval Augmented Generation (RAG)
pipelines. RAG systems are composed of a retrieval and an LLM based generation
module, and provide LLMs with knowledge from a reference textual database,
which enables them to act as a natural language layer between a user and
textual databases, reducing the risk of hallucinations. Evaluating RAG
architectures is, however, challenging because there are several dimensions to
consider: the ability of the retrieval system to identify relevant and focused
context passages, the ability of the LLM to exploit such passages in a faithful
way, or the quality of the generation itself. With Ragas, we put forward a
suite of metrics which can be used to evaluate these different dimensions
\textit\{without having to rely on ground truth human annotations\}. We posit
that such a framework can crucially contribute to faster evaluation cycles of
RAG architectures, which is especially important given the fast adoption of
LLMs.