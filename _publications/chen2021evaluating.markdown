---
layout: publication
title: Evaluating Large Language Models Trained On Code
authors: Chen et al.
conference: Arxiv
year: 2021
bibkey: chen2021evaluating
citations: 1240
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.03374'}]
tags: [GPT, Prompting, Evaluation, Model Architecture, Security, Responsible AI, LLM
    For Code]
---
We introduce Codex, a GPT language model fine-tuned on publicly available
code from GitHub, and study its Python code-writing capabilities. A distinct
production version of Codex powers GitHub Copilot. On HumanEval, a new
evaluation set we release to measure functional correctness for synthesizing
programs from docstrings, our model solves 28.8% of the problems, while GPT-3
solves 0% and GPT-J solves 11.4%. Furthermore, we find that repeated sampling
from the model is a surprisingly effective strategy for producing working
solutions to difficult prompts. Using this method, we solve 70.2% of our
problems with 100 samples per problem. Careful investigation of our model
reveals its limitations, including difficulty with docstrings describing long
chains of operations and with binding operations to variables. Finally, we
discuss the potential broader impacts of deploying powerful code generation
technologies, covering safety, security, and economics.