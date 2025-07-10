---
layout: publication
title: 'Instructdial: Improving Zero And Few-shot Generalization In Dialogue Through
  Instruction Tuning'
authors: Prakhar Gupta et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
citations: 17
bibkey: gupta2022improving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12673'}]
tags: [Tools, RAG, Evaluation, Few-Shot]
---
Instruction tuning is an emergent paradigm in NLP wherein natural language
instructions are leveraged with language models to induce zero-shot performance
on unseen tasks. Instructions have been shown to enable good performance on
unseen tasks and datasets in both large and small language models. Dialogue is
an especially interesting area to explore instruction tuning because dialogue
systems perform multiple kinds of tasks related to language (e.g., natural
language understanding and generation, domain-specific interaction), yet
instruction tuning has not been systematically explored for dialogue-related
tasks. We introduce InstructDial, an instruction tuning framework for dialogue,
which consists of a repository of 48 diverse dialogue tasks in a unified
text-to-text format created from 59 openly available dialogue datasets. Next,
we explore cross-task generalization ability on models tuned on InstructDial
across diverse dialogue tasks. Our analysis reveals that InstructDial enables
good zero-shot performance on unseen datasets and tasks such as dialogue
evaluation and intent detection, and even better performance in a few-shot
setting. To ensure that models adhere to instructions, we introduce novel
meta-tasks. We establish benchmark zero-shot and few-shot performance of models
trained using the proposed framework on multiple dialogue tasks.