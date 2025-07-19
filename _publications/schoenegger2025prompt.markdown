---
layout: publication
title: Prompt Engineering Large Language Models' Forecasting Capabilities
authors: Schoenegger et al.
conference: Algorithms for Intelligent Systems
year: 2025
bibkey: schoenegger2025prompt
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.01578'}]
tags: [RAG, Training Techniques, GPT, Alt, Prompting, Model Architecture, Time Series,
  Fine Tuning]
---
Large language model performance can be improved in a large number of ways. Many such techniques, like fine-tuning or advanced tool usage, are time-intensive and expensive. Although prompt engineering is significantly cheaper and often works for simpler tasks, it remains unclear whether prompt engineering suffices for more complex domains like forecasting. Here we show that small prompt modifications rarely boost forecasting accuracy beyond a minimal baseline. In our first study, we tested 38 prompts across Claude 3.5 Sonnet, Claude 3.5 Haiku, GPT-4o, and Llama 3.1 405B. In our second, we introduced compound prompts and prompts from external sources, also including the reasoning models o1 and o1-mini. Our results show that most prompts lead to negligible gains, although references to base rates yield slight benefits. Surprisingly, some strategies showed strong negative effects on accuracy: especially encouraging the model to engage in Bayesian reasoning. These results suggest that, in the context of complex tasks like forecasting, basic prompt refinements alone offer limited gains, implying that more robust or specialized techniques may be required for substantial performance improvements in AI forecasting.