---
layout: publication
title: 'Gpt-fathom: Benchmarking Large Language Models To Decipher The Evolutionary
  Path Towards GPT-4 And Beyond'
authors: Shen Zheng, Yuyu Zhang, Yijie Zhu, Chenguang Xi, Pengyang Gao, Xun Zhou,
  Kevin Chen-chuan Chang
conference: Angewandte Chemie International Edition
year: 2023
bibkey: zheng2023gpt
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.16583'}]
tags: ["Evaluation", "Model Architecture", "Tools"]
short_authors: Zheng et al.
---
With the rapid advancement of large language models (LLMs), there is a
pressing need for a comprehensive evaluation suite to assess their capabilities
and limitations. Existing LLM leaderboards often reference scores reported in
other papers without consistent settings and prompts, which may inadvertently
encourage cherry-picking favored settings and prompts for better results. In
this work, we introduce GPT-Fathom, an open-source and reproducible LLM
evaluation suite built on top of OpenAI Evals. We systematically evaluate 10+
leading LLMs as well as OpenAI's legacy models on 20+ curated benchmarks across
7 capability categories, all under aligned settings. Our retrospective study on
OpenAI's earlier models offers valuable insights into the evolutionary path
from GPT-3 to GPT-4. Currently, the community is eager to know how GPT-3
progressively improves to GPT-4, including technical details like whether
adding code data improves LLM's reasoning capability, which aspects of LLM
capability can be improved by SFT and RLHF, how much is the alignment tax, etc.
Our analysis sheds light on many of these questions, aiming to improve the
transparency of advanced LLMs.