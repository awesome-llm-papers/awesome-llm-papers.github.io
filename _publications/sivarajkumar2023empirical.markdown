---
layout: publication
title: An Empirical Evaluation Of Prompting Strategies For Large Language Models In
  Zero-shot Clinical Natural Language Processing
authors: Sivarajkumar et al.
conference: JMIR Medical Informatics
year: 2023
bibkey: sivarajkumar2023empirical
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.08008'}]
tags: [Training Techniques, GPT, Prompting, Evaluation, In Context Learning, Model
    Architecture, Few Shot]
---
Large language models (LLMs) have shown remarkable capabilities in Natural
Language Processing (NLP), especially in domains where labeled data is scarce
or expensive, such as clinical domain. However, to unlock the clinical
knowledge hidden in these LLMs, we need to design effective prompts that can
guide them to perform specific clinical NLP tasks without any task-specific
training data. This is known as in-context learning, which is an art and
science that requires understanding the strengths and weaknesses of different
LLMs and prompt engineering approaches. In this paper, we present a
comprehensive and systematic experimental study on prompt engineering for five
clinical NLP tasks: Clinical Sense Disambiguation, Biomedical Evidence
Extraction, Coreference Resolution, Medication Status Extraction, and
Medication Attribute Extraction. We assessed the prompts proposed in recent
literature, including simple prefix, simple cloze, chain of thought, and
anticipatory prompts, and introduced two new types of prompts, namely heuristic
prompting and ensemble prompting. We evaluated the performance of these prompts
on three state-of-the-art LLMs: GPT-3.5, BARD, and LLAMA2. We also contrasted
zero-shot prompting with few-shot prompting, and provide novel insights and
guidelines for prompt engineering for LLMs in clinical NLP. To the best of our
knowledge, this is one of the first works on the empirical evaluation of
different prompt engineering approaches for clinical NLP in this era of
generative AI, and we hope that it will inspire and inform future research in
this area.