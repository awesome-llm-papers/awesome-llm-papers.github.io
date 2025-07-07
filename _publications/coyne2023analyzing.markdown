---
layout: publication
title: Analyzing The Performance Of GPT-3.5 And GPT-4 In Grammatical Error Correction
authors: Steven Coyne, Keisuke Sakaguchi, Diana Galvan-sosa, Michael Zock, Kentaro
  Inui
conference: Arxiv
year: 2023
citations: 16
bibkey: coyne2023analyzing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.14342'}]
tags: [Few-Shot, GPT, Model Architecture, Prompting]
---
GPT-3 and GPT-4 models are powerful, achieving high performance on a variety
of Natural Language Processing tasks. However, there is a relative lack of
detailed published analysis of their performance on the task of grammatical
error correction (GEC). To address this, we perform experiments testing the
capabilities of a GPT-3.5 model (text-davinci-003) and a GPT-4 model
(gpt-4-0314) on major GEC benchmarks. We compare the performance of different
prompts in both zero-shot and few-shot settings, analyzing intriguing or
problematic outputs encountered with different prompt formats. We report the
performance of our best prompt on the BEA-2019 and JFLEG datasets, finding that
the GPT models can perform well in a sentence-level revision setting, with
GPT-4 achieving a new high score on the JFLEG benchmark. Through human
evaluation experiments, we compare the GPT models' corrections to source, human
reference, and baseline GEC system sentences and observe differences in editing
strategies and how they are scored by human raters.