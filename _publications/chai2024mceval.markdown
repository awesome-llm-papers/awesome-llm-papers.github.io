---
layout: publication
title: 'Mceval: Massively Multilingual Code Evaluation'
authors: Linzheng Chai, Shukai Liu, Jian Yang, Yuwei Yin, Ke Jin, Jiaheng Liu, Tao
  Sun, Ge Zhang, Changyu Ren, Hongcheng Guo, Zekun Wang, Boyang Wang, Xianjie Wu,
  Bing Wang, Tongliang Li, Liqun Yang, Sufeng Duan, Zhoujun Li
conference: No Venue
year: 2024
bibkey: chai2024mceval
additional_links: [{name: Code, url: 'https://mceval.github.io/'}, {name: Code, url: 'https://huggingface.co/discussions/paper/666913367acc6e95a98c809c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.07436'}]
tags: ["Evaluation", "Has Code"]
short_authors: Chai et al.
---
Code large language models (LLMs) have shown remarkable advances in code understanding, completion, and generation tasks. Programming benchmarks, comprised of a selection of code challenges and corresponding test cases, serve as a standard to evaluate the capability of different LLMs in such tasks. However, most existing benchmarks primarily focus on Python and are still restricted to a limited number of languages, where other languages are translated from the Python samples (e.g. MultiPL-E) degrading the data diversity. To further facilitate the research of code LLMs, we propose a massively multilingual code benchmark covering 40 programming languages (McEval) with 16K test samples, which substantially pushes the limits of code LLMs in multilingual scenarios. The benchmark contains challenging code completion, understanding, and generation evaluation tasks with finely curated massively multilingual instruction corpora McEval-Instruct. In addition, we introduce an effective multilingual coder mCoder trained on McEval-Instruct to support multilingual programming language generation. Extensive experimental results on McEval show that there is still a difficult journey between open-source models and closed-source LLMs (e.g. GPT-series models) in numerous languages. The instruction corpora, evaluation benchmark, and leaderboard are available at https://mceval.github.io/.

https://huggingface.co/discussions/paper/666913367acc6e95a98c809c