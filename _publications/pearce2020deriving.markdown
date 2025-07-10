---
layout: publication
title: 'DAVE: Deriving Automatically Verilog From English'
authors: Hammond Pearce, Benjamin Tan, Ramesh Karri
conference: 'MLCAD ''20: 2020 ACM/IEEE Workshop on Machine Learning for CAD'
year: 2020
citations: 37
bibkey: pearce2020deriving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.01026'}]
tags: [Model Architecture, GPT, Fine-Tuning, RAG, Training Techniques]
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