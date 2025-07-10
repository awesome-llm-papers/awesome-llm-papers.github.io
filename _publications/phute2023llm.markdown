---
layout: publication
title: 'LLM Self Defense: By Self Examination, Llms Know They Are Being Tricked'
authors: Mansi Phute et al.
conference: Arxiv
year: 2023
citations: 20
bibkey: phute2023llm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.07308'}, {name: Code,
    url: 'https://github.com/poloclub/llm-self-defense'}]
tags: [Responsible AI, Language Modeling, Security, Has Code, Model Architecture,
  GPT, Fine-Tuning, Reinforcement Learning, Prompting, Agentic, Training Techniques]
---
Large language models (LLMs) are popular for high-quality text generation but
can produce harmful content, even when aligned with human values through
reinforcement learning. Adversarial prompts can bypass their safety measures.
We propose LLM Self Defense, a simple approach to defend against these attacks
by having an LLM screen the induced responses. Our method does not require any
fine-tuning, input preprocessing, or iterative output generation. Instead, we
incorporate the generated content into a pre-defined prompt and employ another
instance of an LLM to analyze the text and predict whether it is harmful. We
test LLM Self Defense on GPT 3.5 and Llama 2, two of the current most prominent
LLMs against various types of attacks, such as forcefully inducing affirmative
responses to prompts and prompt engineering attacks. Notably, LLM Self Defense
succeeds in reducing the attack success rate to virtually 0 using both GPT 3.5
and Llama 2. The code is publicly available at
https://github.com/poloclub/llm-self-defense