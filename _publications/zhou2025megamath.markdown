---
layout: publication
title: 'Megamath: Pushing The Limits Of Open Math Corpora'
authors: Fan Zhou, Zengzhi Wang, Nikhil Ranjan, Zhoujun Cheng, Liping Tang, Guowei
  He, Zhengzhong Liu, Eric P. Xing
conference: No Venue
year: 2025
bibkey: zhou2025megamath
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67efe6e939d83c66f96ef08d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.02807'}]
tags: ["Datasets"]
short_authors: Zhou et al.
---
Mathematical reasoning is a cornerstone of human intelligence and a key benchmark for advanced capabilities in large language models (LLMs). However, the research community still lacks an open, large-scale, high-quality corpus tailored to the demands of math-centric LLM pre-training. We present MegaMath, an open dataset curated from diverse, math-focused sources through following practices: (1) Revisiting web data: We re-extracted mathematical documents from Common Crawl with math-oriented HTML optimizations, fasttext-based filtering and deduplication, all for acquiring higher-quality data on the Internet. (2) Recalling Math-related code data: We identified high quality math-related code from large code training corpus, Stack-V2, further enhancing data diversity. (3) Exploring Synthetic data: We synthesized QA-style text, math-related code, and interleaved text-code blocks from web data or code data. By integrating these strategies and validating their effectiveness through extensive ablations, MegaMath delivers 371B tokens with the largest quantity and top quality among existing open math pre-training datasets.

https://huggingface.co/discussions/paper/67efe6e939d83c66f96ef08d