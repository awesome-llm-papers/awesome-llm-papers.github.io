---
layout: publication
title: Large Language Models As Misleading Assistants In Conversation
authors: Betty Li Hou, Kejian Shi, Jason Phang, James Aung, Steven Adler, Rosie Campbell
conference: Lecture Notes in Computer Science
year: 2024
bibkey: hou2024large
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.11789'}]
tags: ["Model Architecture"]
short_authors: Hou et al.
---
Large Language Models (LLMs) are able to provide assistance on a wide range
of information-seeking tasks. However, model outputs may be misleading, whether
unintentionally or in cases of intentional deception. We investigate the
ability of LLMs to be deceptive in the context of providing assistance on a
reading comprehension task, using LLMs as proxies for human users. We compare
outcomes of (1) when the model is prompted to provide truthful assistance, (2)
when it is prompted to be subtly misleading, and (3) when it is prompted to
argue for an incorrect answer. Our experiments show that GPT-4 can effectively
mislead both GPT-3.5-Turbo and GPT-4, with deceptive assistants resulting in up
to a 23% drop in accuracy on the task compared to when a truthful assistant is
used. We also find that providing the user model with additional context from
the passage partially mitigates the influence of the deceptive model. This work
highlights the ability of LLMs to produce misleading information and the
effects this may have in real-world situations.