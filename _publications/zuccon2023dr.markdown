---
layout: publication
title: 'Dr Chatgpt, Tell Me What I Want To Hear: How Prompt Knowledge Impacts Health
  Answer Correctness'
authors: Guido Zuccon, Bevan Koopman
conference: Arxiv
year: 2023
citations: 22
bibkey: zuccon2023dr
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.13793'}]
tags: [Model Architecture, GPT, RAG, Prompting, Pre-Training, Training Techniques]
---
Generative pre-trained language models (GPLMs) like ChatGPT encode in the
model's parameters knowledge the models observe during the pre-training phase.
This knowledge is then used at inference to address the task specified by the
user in their prompt. For example, for the question-answering task, the GPLMs
leverage the knowledge and linguistic patterns learned at training to produce
an answer to a user question. Aside from the knowledge encoded in the model
itself, answers produced by GPLMs can also leverage knowledge provided in the
prompts. For example, a GPLM can be integrated into a retrieve-then-generate
paradigm where a search engine is used to retrieve documents relevant to the
question; the content of the documents is then transferred to the GPLM via the
prompt. In this paper we study the differences in answer correctness generated
by ChatGPT when leveraging the model's knowledge alone vs. in combination with
the prompt knowledge. We study this in the context of consumers seeking health
advice from the model. Aside from measuring the effectiveness of ChatGPT in
this context, we show that the knowledge passed in the prompt can overturn the
knowledge encoded in the model and this is, in our experiments, to the
detriment of answer correctness. This work has important implications for the
development of more robust and transparent question-answering systems based on
generative pre-trained language models.