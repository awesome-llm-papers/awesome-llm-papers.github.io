---
layout: publication
title: On Second Thought, Let's Not Think Step By Step! Bias And Toxicity In Zero-shot
  Reasoning
authors: Omar Shaikh, Hongxin Zhang, William Held, Michael Bernstein, Diyi Yang
conference: Arxiv
year: 2022
citations: 24
bibkey: shaikh2022second
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.08061'}]
tags: [Ethics and Bias, Prompting]
---
Generating a Chain of Thought (CoT) has been shown to consistently improve
large language model (LLM) performance on a wide range of NLP tasks. However,
prior work has mainly focused on logical reasoning tasks (e.g. arithmetic,
commonsense QA); it remains unclear whether improvements hold for more diverse
types of reasoning, especially in socially situated contexts. Concretely, we
perform a controlled evaluation of zero-shot CoT across two socially sensitive
domains: harmful questions and stereotype benchmarks. We find that zero-shot
CoT reasoning in sensitive domains significantly increases a model's likelihood
to produce harmful or undesirable output, with trends holding across different
prompt formats and model variants. Furthermore, we show that harmful CoTs
increase with model size, but decrease with improved instruction following. Our
work suggests that zero-shot CoT should be used with caution on socially
important tasks, especially when marginalized groups or sensitive topics are
involved.