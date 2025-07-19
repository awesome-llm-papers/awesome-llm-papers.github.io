---
layout: publication
title: 'Chatie: Zero-shot Information Extraction Via Chatting With Chatgpt'
authors: Wei et al.
conference: International Journal of Medical Informatics
year: 2023
bibkey: wei2023chatie
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.10205'}]
tags: [GPT, Prompting, Tools, Model Architecture, Reinforcement Learning, Datasets]
---
Zero-shot information extraction (IE) aims to build IE systems from the
unannotated text. It is challenging due to involving little human intervention.
Challenging but worthwhile, zero-shot IE reduces the time and effort that data
labeling takes. Recent efforts on large language models (LLMs, e.g., GPT-3,
ChatGPT) show promising performance on zero-shot settings, thus inspiring us to
explore prompt-based methods. In this work, we ask whether strong IE models can
be constructed by directly prompting LLMs. Specifically, we transform the
zero-shot IE task into a multi-turn question-answering problem with a two-stage
framework (ChatIE). With the power of ChatGPT, we extensively evaluate our
framework on three IE tasks: entity-relation triple extract, named entity
recognition, and event extraction. Empirical results on six datasets across two
languages show that ChatIE achieves impressive performance and even surpasses
some full-shot models on several datasets (e.g., NYT11-HRL). We believe that
our work could shed light on building IE models with limited resources.