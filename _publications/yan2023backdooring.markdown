---
layout: publication
title: Backdooring Instruction-tuned Large Language Models With Virtual Prompt Injection
authors: Jun Yan et al.
conference: 'Proceedings of the 2024 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies (Volume 1:
  Long Papers)'
year: 2023
citations: 16
bibkey: yan2023backdooring
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.16888'}]
tags: [Security, Ethics and Bias, Applications, Tools, Prompting, Training Techniques]
---
Instruction-tuned Large Language Models (LLMs) have become a ubiquitous
platform for open-ended applications due to their ability to modulate responses
based on human instructions. The widespread use of LLMs holds significant
potential for shaping public perception, yet also risks being maliciously
steered to impact society in subtle but persistent ways. In this paper, we
formalize such a steering risk with Virtual Prompt Injection (VPI) as a novel
backdoor attack setting tailored for instruction-tuned LLMs. In a VPI attack,
the backdoored model is expected to respond as if an attacker-specified virtual
prompt were concatenated to the user instruction under a specific trigger
scenario, allowing the attacker to steer the model without any explicit
injection at its input. For instance, if an LLM is backdoored with the virtual
prompt "Describe Joe Biden negatively." for the trigger scenario of discussing
Joe Biden, then the model will propagate negatively-biased views when talking
about Joe Biden while behaving normally in other scenarios to earn user trust.
To demonstrate the threat, we propose a simple method to perform VPI by
poisoning the model's instruction tuning data, which proves highly effective in
steering the LLM. For example, by poisoning only 52 instruction tuning examples
(0.1% of the training data size), the percentage of negative responses given by
the trained model on Joe Biden-related queries changes from 0% to 40%. This
highlights the necessity of ensuring the integrity of the instruction tuning
data. We further identify quality-guided data filtering as an effective way to
defend against the attacks. Our project page is available at
https://poison-llm.github.io.