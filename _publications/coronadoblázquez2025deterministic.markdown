---
layout: publication
title: Deterministic Or Probabilistic? The Psychology Of Llms As Random Number Generators
authors: "Coronado-bl\xE1zquez Javier"
conference: Arxiv
year: 2025
bibkey: "coronadobl\xE1zquez2025deterministic"
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.19965'}]
tags: [Training Techniques, Prompting, Ethics And Bias, Transformer, Model Architecture,
  Language Modeling]
---
Large Language Models (LLMs) have transformed text generation through
inherently probabilistic context-aware mechanisms, mimicking human natural
language. In this paper, we systematically investigate the performance of
various LLMs when generating random numbers, considering diverse configurations
such as different model architectures, numerical ranges, temperature, and
prompt languages. Our results reveal that, despite their stochastic
transformers-based architecture, these models often exhibit deterministic
responses when prompted for random numerical outputs. In particular, we find
significant differences when changing the model, as well as the prompt
language, attributing this phenomenon to biases deeply embedded within the
training data. Models such as DeepSeek-R1 can shed some light on the internal
reasoning process of LLMs, despite arriving to similar results. These biases
induce predictable patterns that undermine genuine randomness, as LLMs are
nothing but reproducing our own human cognitive biases.