---
layout: publication
title: 'Skywork R1V: Pioneering Multimodal Reasoning With Chain-of-thought'
authors: Yi Peng, Chris, Xiaokun Wang, Yichen Wei, Jiangbo Pei, Weijie Qiu, Ai Jian,
  Yunzhuo Hao, Jiachun Pan, Tianyidan Xie, Li Ge, Rongxian Zhuang, Xuchen Song, Yang
  Liu, Yahui Zhou
conference: No Venue
year: 2025
bibkey: peng2025skywork
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67f61a9daf81b0685bf05731'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.05599'}]
tags: ["Efficiency", "Evaluation", "Fine-Tuning", "Prompting"]
short_authors: Peng et al.
---
We introduce Skywork R1V, a multimodal reasoning model extending the an R1-series Large language models (LLM) to visual modalities via an efficient multimodal transfer method. Leveraging a lightweight visual projector, Skywork R1V facilitates seamless multimodal adaptation without necessitating retraining of either the foundational language model or the vision encoder. To strengthen visual-text alignment, we propose a hybrid optimization strategy that combines Iterative Supervised Fine-Tuning (SFT) with Group Relative Policy Optimization (GRPO), significantly enhancing cross-modal integration efficiency. Additionally, we introduce an adaptive-length Chain-of-Thought distillation approach for reasoning data generation. This approach dynamically optimizes reasoning chain lengths, thereby enhancing inference efficiency and preventing excessive reasoning overthinking. Empirical evaluations demonstrate that Skywork R1V, with only 38B parameters, delivers competitive performance, achieving a score of 69.0 on the MMMU benchmark and 67.5 on MathVista. Meanwhile, it maintains robust textual reasoning performance, evidenced by impressive scores of 72.0 on AIME and 94.0 on MATH500. The Skywork R1V model weights have been publicly released to promote openness and reproducibility.

https://huggingface.co/discussions/paper/67f61a9daf81b0685bf05731