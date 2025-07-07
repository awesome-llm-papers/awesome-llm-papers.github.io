---
layout: publication
title: 'DAVE: Deriving Automatically Verilog From English'
authors: Hammond Pearce, Benjamin Tan, Ramesh Karri
conference: Arxiv
year: 2020
citations: 36
bibkey: pearce2020deriving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.01026'}]
tags: [Training Techniques, GPT, RAG, Fine-Tuning, Model Architecture]
---
While specifications for digital systems are provided in natural language,
engineers undertake significant efforts to translate them into the programming
languages understood by compilers for digital systems. Automating this process
allows designers to work with the language in which they are most comfortable
--the original natural language -- and focus instead on other downstream design
challenges. We explore the use of state-of-the-art machine learning (ML) to
automatically derive Verilog snippets from English via fine-tuning GPT-2, a
natural language ML system. We describe our approach for producing a suitable
dataset of novice-level digital design tasks and provide a detailed exploration
of GPT-2, finding encouraging translation performance across our task sets
(94.8% correct), with the ability to handle both simple and abstract design
tasks.