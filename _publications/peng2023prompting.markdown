---
layout: publication
title: Prompting The Hidden Talent Of Web-scale Speech Models For Zero-shot Task Generalization
authors: Puyuan Peng, Brian Yan, Shinji Watanabe, David Harwath
conference: INTERSPEECH 2023
year: 2023
citations: 23
bibkey: peng2023prompting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.11095'}, {name: Code,
    url: 'https://github.com/jasonppy/PromptingWhisper'}]
tags: [Security, Has Code, Ethics and Bias, RAG, Prompting, INTERSPEECH]
---
We investigate the emergent abilities of the recently proposed web-scale
speech model Whisper, by adapting it to unseen tasks with prompt engineering.
We selected three tasks: audio-visual speech recognition (AVSR), code-switched
speech recognition (CS-ASR), and speech translation (ST) on unseen language
pairs. We design task-specific prompts, by either leveraging another
large-scale model, or simply manipulating the special tokens in the default
prompts. Experiments show that compared to the default prompts, our proposed
prompts improve performance by 10% to 45% on the three zero-shot tasks, and
even outperform SotA supervised models on some datasets. In addition, our
experiments reveal many interesting properties of Whisper, including its
robustness to prompts, bias on accents, and the multilingual understanding in
its latent space. Code is available at
https://github.com/jasonppy/PromptingWhisper