---
layout: publication
title: Mitigating Fine-grained Hallucination By Fine-tuning Large Vision-language
  Models With Caption Rewrites
authors: Lei Wang, Jiabang He, Shenshen Li, Ning Liu, Ee-peng Lim
conference: Arxiv
year: 2023
bibkey: lei2023mitigating
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2312.01701v1'}]
tags: [Model Architecture, Multimodal Models, Evaluation, Language Modeling, Fine
    Tuning, GPT, Tools, Training Techniques]
---
Large language models (LLMs) have shown remarkable performance in natural
language processing (NLP) tasks. To comprehend and execute diverse human
instructions over image data, instruction-tuned large vision-language models
(LVLMs) have been introduced. However, LVLMs may suffer from different types of
object hallucinations. Nevertheless, LVLMs are evaluated for coarse-grained
object hallucinations only (i.e., generated objects non-existent in the input
image). The fine-grained object attributes and behaviors non-existent in the
image may still be generated but not measured by the current evaluation
methods. In this paper, we thus focus on reducing fine-grained hallucinations
of LVLMs. We propose \textit\{ReCaption\}, a framework that consists of two
components: rewriting captions using ChatGPT and fine-tuning the
instruction-tuned LVLMs on the rewritten captions. We also propose a
fine-grained probing-based evaluation method named \textit\{Fine-Grained Object
Hallucination Evaluation\} (\textit\{FGHE\}). Our experiment results demonstrate
that ReCaption effectively reduces fine-grained object hallucination for
different LVLM options and improves their text generation quality. The code can
be found at https://github.com/Anonymousanoy/FOHE.