---
layout: publication
title: 'The Instruction Hierarchy: Training Llms To Prioritize Privileged Instructions'
authors: Eric Wallace, Kai Xiao, Reimar Leike, Lilian Weng, Johannes Heidecke, Alex
  Beutel
conference: No Venue
year: 2024
bibkey: wallace2024instruction
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.13208'}]
tags: ["Instruction Following", "Training Techniques"]
short_authors: Wallace et al.
---
Today's LLMs are susceptible to prompt injections, jailbreaks, and other attacks that allow adversaries to overwrite a model's original instructions with their own malicious prompts. In this work, we argue that one of the primary vulnerabilities underlying these attacks is that LLMs often consider system prompts (e.g., text from an application developer) to be the same priority as text from untrusted users and third parties. To address this, we propose an instruction hierarchy that explicitly defines how models should behave when instructions of different priorities conflict. We then propose a data generation method to demonstrate this hierarchical instruction following behavior, which teaches LLMs to selectively ignore lower-privileged instructions. We apply this method to GPT-3.5, showing that it drastically increases robustness -- even for attack types not seen during training -- while imposing minimal degradations on standard capabilities.

https://huggingface.co/discussions/paper/6627260422bdf1d264974ab3