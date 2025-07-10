---
layout: publication
title: Defending Against Backdoor Attacks In Natural Language Generation
authors: Xiaofei Sun et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
citations: 16
bibkey: sun2021defending
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01810'}]
tags: [Security, RAG]
---
The frustratingly fragile nature of neural network models make current
natural language generation (NLG) systems prone to backdoor attacks and
generate malicious sequences that could be sexist or offensive. Unfortunately,
little effort has been invested to how backdoor attacks can affect current NLG
models and how to defend against these attacks. In this work, by giving a
formal definition of backdoor attack and defense, we investigate this problem
on two important NLG tasks, machine translation and dialog generation. Tailored
to the inherent nature of NLG models (e.g., producing a sequence of coherent
words given contexts), we design defending strategies against attacks. We find
that testing the backward probability of generating sources given targets
yields effective defense performance against all different types of attacks,
and is able to handle the \{\it one-to-many\} issue in many NLG tasks such as
dialog generation. We hope that this work can raise the awareness of backdoor
risks concealed in deep NLG systems and inspire more future work (both attack
and defense) towards this direction.