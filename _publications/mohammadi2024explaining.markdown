---
layout: publication
title: Explaining Large Language Models Decisions Using Shapley Values
authors: Mohammadi Behnam
conference: Lecture Notes in Computer Science
year: 2024
bibkey: mohammadi2024explaining
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.01332'}]
tags: [Prompting, Ethics And Bias, Survey Paper, Reinforcement Learning, Applications,
  Security]
---
The emergence of large language models (LLMs) has opened up exciting
possibilities for simulating human behavior and cognitive processes, with
potential applications in various domains, including marketing research and
consumer behavior analysis. However, the validity of utilizing LLMs as
stand-ins for human subjects remains uncertain due to glaring divergences that
suggest fundamentally different underlying processes at play and the
sensitivity of LLM responses to prompt variations. This paper presents a novel
approach based on Shapley values from cooperative game theory to interpret LLM
behavior and quantify the relative contribution of each prompt component to the
model's output. Through two applications - a discrete choice experiment and an
investigation of cognitive biases - we demonstrate how the Shapley value method
can uncover what we term "token noise" effects, a phenomenon where LLM
decisions are disproportionately influenced by tokens providing minimal
informative content. This phenomenon raises concerns about the robustness and
generalizability of insights obtained from LLMs in the context of human
behavior simulation. Our model-agnostic approach extends its utility to
proprietary LLMs, providing a valuable tool for practitioners and researchers
to strategically optimize prompts and mitigate apparent cognitive biases. Our
findings underscore the need for a more nuanced understanding of the factors
driving LLM responses before relying on them as substitutes for human subjects
in survey settings. We emphasize the importance of researchers reporting
results conditioned on specific prompt templates and exercising caution when
drawing parallels between human behavior and LLMs.