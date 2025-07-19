---
layout: publication
title: Infecting Generative AI With Viruses
authors: Noever David, Mckee Forrest
conference: Viruses
year: 2025
bibkey: noever2025infecting
citations: 175
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.05542'}]
tags: [GPT, Tools, Model Architecture, Reinforcement Learning, Security]
---
This study demonstrates a novel approach to testing the security boundaries
of Vision-Large Language Model (VLM/ LLM) using the EICAR test file embedded
within JPEG images. We successfully executed four distinct protocols across
multiple LLM platforms, including OpenAI GPT-4o, Microsoft Copilot, Google
Gemini 1.5 Pro, and Anthropic Claude 3.5 Sonnet. The experiments validated that
a modified JPEG containing the EICAR signature could be uploaded, manipulated,
and potentially executed within LLM virtual workspaces. Key findings include:
1) consistent ability to mask the EICAR string in image metadata without
detection, 2) successful extraction of the test file using Python-based
manipulation within LLM environments, and 3) demonstration of multiple
obfuscation techniques including base64 encoding and string reversal. This
research extends Microsoft Research's "Penetration Testing Rules of Engagement"
framework to evaluate cloud-based generative AI and LLM security boundaries,
particularly focusing on file handling and execution capabilities within
containerized environments.