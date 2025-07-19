---
layout: publication
title: 'Treeprompt: Learning To Compose Tree Prompts For Explainable Visual Grounding'
authors: Zhang et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2023
bibkey: zhang2023treeprompt
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.11497'}]
tags: [Prompting, Interpretability And Explainability, Evaluation, LLM for Code, Multimodal
    Models, Datasets]
---
Prompt tuning has achieved great success in transferring the knowledge from
large pretrained vision-language models into downstream tasks, and has
dominated the performance on visual grounding (VG). However, almost all
existing prompt tuning paradigms suffer from poor interpretability. In this
paper, we argue that their poor interpretability is attributed to the holistic
prompt generation and inference process. By "holistic", we mean that they
usually directly learn a set of vectors as the prompt (i.e., prompt
generation), and use the learned global prompt to augment the textual input for
the VG model (i.e., prompt inference). To this end, we propose a new prompt
construction paradigm with explicit explainable ability, named TreePrompt.
Specifically, we first deconstruct a complex sentence into a tree, that is
consistent with human reasoning. Then, following the syntax tree, we compose a
structured prompt in a bottom-up manner. Thanks to this step-by-step prompt
construction process, each intermediate prompt (i.e., tree node) permits us to
understand the reasoning process. Extensive ablations on various backbones and
benchmarks consistently demonstrate the effectiveness and interpretability of
our TreePrompt.