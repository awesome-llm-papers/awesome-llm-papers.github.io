---
layout: publication
title: Chatgpt Hallucinates When Attributing Answers
authors: Guido Zuccon, Bevan Koopman, Razia Shaik
conference: Arxiv
year: 2023
citations: 27
bibkey: zuccon2023chatgpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.09401'}]
tags: [GPT, RAG, Reinforcement Learning, Prompting, Model Architecture]
---
Can ChatGPT provide evidence to support its answers? Does the evidence it
suggests actually exist and does it really support its answer? We investigate
these questions using a collection of domain-specific knowledge-based
questions, specifically prompting ChatGPT to provide both an answer and
supporting evidence in the form of references to external sources. We also
investigate how different prompts impact answers and evidence. We find that
ChatGPT provides correct or partially correct answers in about half of the
cases (50.6% of the times), but its suggested references only exist 14% of the
times. We further provide insights on the generated references that reveal
common traits among the references that ChatGPT generates, and show how even if
a reference provided by the model does exist, this reference often does not
support the claims ChatGPT attributes to it. Our findings are important because
(1) they are the first systematic analysis of the references created by ChatGPT
in its answers; (2) they suggest that the model may leverage good quality
information in producing correct answers, but is unable to attribute real
evidence to support its answers. Prompts, raw result files and manual analysis
are made publicly available.