---
layout: publication
title: Legal Prompt Engineering For Multilingual Legal Judgement Prediction
authors: Dietrich Trautmann, Alina Petrova, Frank Schilder
conference: Arxiv
year: 2022
citations: 23
bibkey: trautmann2022legal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.02199'}]
tags: [Fine-Tuning, Reinforcement Learning, Training Techniques, Prompting]
---
Legal Prompt Engineering (LPE) or Legal Prompting is a process to guide and
assist a large language model (LLM) with performing a natural legal language
processing (NLLP) skill. Our goal is to use LPE with LLMs over long legal
documents for the Legal Judgement Prediction (LJP) task. We investigate the
performance of zero-shot LPE for given facts in case-texts from the European
Court of Human Rights (in English) and the Federal Supreme Court of Switzerland
(in German, French and Italian). Our results show that zero-shot LPE is better
compared to the baselines, but it still falls short compared to current state
of the art supervised approaches. Nevertheless, the results are important,
since there was 1) no explicit domain-specific data used - so we show that the
transfer to the legal domain is possible for general-purpose LLMs, and 2) the
LLMs where directly applied without any further training or fine-tuning - which
in turn saves immensely in terms of additional computational costs.