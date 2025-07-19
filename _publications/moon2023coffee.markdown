---
layout: publication
title: 'Coffee: Boost Your Code Llms By Fixing Bugs With Feedback'
authors: Moon et al.
conference: Proceedings of the Genetic and Evolutionary Computation Conference Companion
year: 2023
bibkey: moon2023coffee
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.07215'}]
tags: [RAG, GPT, Tools, Evaluation, Model Architecture, Datasets]
---
Code editing is an essential step towards reliable program synthesis to
automatically correct critical errors generated from code LLMs. Recent studies
have demonstrated that closed-source LLMs (i.e., ChatGPT and GPT-4) are capable
of generating corrective feedback to edit erroneous inputs. However, it remains
challenging for open-source code LLMs to generate feedback for code editing,
since these models tend to adhere to the superficial formats of feedback and
provide feedback with misleading information. Hence, the focus of our work is
to leverage open-source code LLMs to generate helpful feedback with correct
guidance for code editing. To this end, we present Coffee, a collected dataset
specifically designed for code fixing with feedback. Using this dataset, we
construct CoffeePots, a framework for COde Fixing with FEEdback via
Preference-Optimized Tuning and Selection. The proposed framework aims to
automatically generate helpful feedback for code editing while minimizing the
potential risk of superficial feedback. The combination of Coffee and
CoffeePots marks a significant advancement, achieving state-of-the-art
performance on HumanEvalFix benchmark. Codes and model checkpoints are publicly
available at https://github.com/Lune-Blue/COFFEE.