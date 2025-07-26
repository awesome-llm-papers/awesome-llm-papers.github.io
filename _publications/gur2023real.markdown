---
layout: publication
title: A Real-world Webagent With Planning, Long Context Understanding, And Program
  Synthesis
authors: Izzeddin Gur, Hiroki Furuta, Austin Huang, Mustafa Safdari, Yutaka Matsuo,
  Douglas Eck, Aleksandra Faust
conference: No Venue
year: 2023
bibkey: gur2023real
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/64bf412146cc3cdfbb29e8ac'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2307.12856'}]
tags: ["Agentic", "Llm For Code", "Memory & Context", "Model Architecture"]
short_authors: Gur et al.
---
Pre-trained large language models (LLMs) have recently achieved better generalization and sample efficiency in autonomous web navigation. However, the performance on real-world websites has still suffered from (1) open domainness, (2) limited context length, and (3) lack of inductive bias on HTML. We introduce WebAgent, an LLM-driven agent that can complete the tasks on real websites following natural language instructions. WebAgent plans ahead by decomposing instructions into canonical sub-instructions, summarizes long HTML documents into task-relevant snippets, and acts on websites via generated Python programs from those. We design WebAgent with Flan-U-PaLM, for grounded code generation, and HTML-T5, new pre-trained LLMs for long HTML documents using local and global attention mechanisms and a mixture of long-span denoising objectives, for planning and summarization. We empirically demonstrate that our recipe improves the success on a real website by over 50%, and that HTML-T5 is the best model to solve HTML-based tasks; achieving 14.9% higher success rate than prior SoTA on the MiniWoB web navigation benchmark and better accuracy on offline task planning evaluation.

https://huggingface.co/discussions/paper/64bf412146cc3cdfbb29e8ac