---
layout: publication
title: 'Judgebench: A Benchmark For Evaluating Llm-based Judges'
authors: Sijun Tan, Siyuan Zhuang, Kyle Montgomery, William Y. Tang, Alejandro Cuadron,
  Chenguang Wang, Raluca Ada Popa, Ion Stoica
conference: No Venue
year: 2024
bibkey: tan2024judgebench
additional_links: [{name: Code, url: 'https://github.com/ScalerLab/JudgeBench'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/67113ed43a90c03ce46e7f52'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.12784'}]
tags: ["Evaluation", "Has Code", "Tools"]
short_authors: Tan et al.
---
LLM-based judges have emerged as a scalable alternative to human evaluation and are increasingly used to assess, compare, and improve models. However, the reliability of LLM-based judges themselves is rarely scrutinized. As LLMs become more advanced, their responses grow more sophisticated, requiring stronger judges to evaluate them. Existing benchmarks primarily focus on a judge's alignment with human preferences, but often fail to account for more challenging tasks where crowdsourced human preference is a poor indicator of factual and logical correctness. To address this, we propose a novel evaluation framework to objectively evaluate LLM-based judges. Based on this framework, we propose JudgeBench, a benchmark for evaluating LLM-based judges on challenging response pairs spanning knowledge, reasoning, math, and coding. JudgeBench leverages a novel pipeline for converting existing difficult datasets into challenging response pairs with preference labels reflecting objective correctness. Our comprehensive evaluation on a collection of prompted judges, fine-tuned judges, multi-agent judges, and reward models shows that JudgeBench poses a significantly greater challenge than previous benchmarks, with many strong models (e.g., GPT-4o) performing just slightly better than random guessing. Overall, JudgeBench offers a reliable platform for assessing increasingly advanced LLM-based judges. Data and code are available at https://github.com/ScalerLab/JudgeBench .

https://huggingface.co/discussions/paper/67113ed43a90c03ce46e7f52