---
layout: publication
title: Building Open-retrieval Conversational Question Answering Systems By Generating
  Synthetic Data And Decontextualizing User Questions
authors: Vlachos et al.
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2025
bibkey: vlachos2025building
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.04884'}]
tags: [RAG, Training Techniques, Tools, Reinforcement Learning, SIGIR, Applications,
  Datasets]
---
We consider open-retrieval conversational question answering (OR-CONVQA), an extension of question answering where system responses need to be (i) aware of dialog history and (ii) grounded in documents (or document fragments) retrieved per question. Domain-specific OR-CONVQA training datasets are crucial for real-world applications, but hard to obtain. We propose a pipeline that capitalizes on the abundance of plain text documents in organizations (e.g., product documentation) to automatically produce realistic OR-CONVQA dialogs with annotations. Similarly to real-world humanannotated OR-CONVQA datasets, we generate in-dialog question-answer pairs, self-contained (decontextualized, e.g., no referring expressions) versions of user questions, and propositions (sentences expressing prominent information from the documents) the system responses are grounded in. We show how the synthetic dialogs can be used to train efficient question rewriters that decontextualize user questions, allowing existing dialog-unaware retrievers to be utilized. The retrieved information and the decontextualized question are then passed on to an LLM that generates the system's response.