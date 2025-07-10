---
layout: publication
title: 'Expertprompting: Instructing Large Language Models To Be Distinguished Experts'
authors: Benfeng Xu et al.
conference: Arxiv
year: 2023
citations: 29
bibkey: xu2023instructing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14688'}, {name: Code,
    url: 'https://github.com/OFA-Sys/ExpertLLaMA'}]
tags: [Has Code, Model Architecture, Reinforcement Learning, In-Context Learning,
  Prompting, Agentic, GPT, Evaluation]
---
The answering quality of an aligned large language model (LLM) can be
drastically improved if treated with proper crafting of prompts. In this paper,
we propose ExpertPrompting to elicit the potential of LLMs to answer as
distinguished experts. We first utilize In-Context Learning to automatically
synthesize detailed and customized descriptions of the expert identity for each
specific instruction, and then ask LLMs to provide answer conditioned on such
agent background. Based on this augmented prompting strategy, we produce a new
set of instruction-following data using GPT-3.5, and train a competitive
open-source chat assistant called ExpertLLaMA. We employ GPT4-based evaluation
to show that 1) the expert data is of significantly higher quality than vanilla
answers, and 2) ExpertLLaMA outperforms existing open-source opponents and
achieves 96% of the original ChatGPT's capability. All data and the
ExpertLLaMA model will be made publicly available at
https://github.com/OFA-Sys/ExpertLLaMA.