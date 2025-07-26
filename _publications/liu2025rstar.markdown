---
layout: publication
title: 'Rstar-coder: Scaling Competitive Code Reasoning With A Large-scale Verified
  Dataset'
authors: Yifei Liu, Li Lyna Zhang, Yi Zhu, Bingcheng Dong, Xudong Zhou, Ning Shang,
  Fan Yang, Mao Yang
conference: No Venue
year: 2025
bibkey: liu2025rstar
additional_links: [{name: Code, url: 'https://github.com/microsoft/rStar'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/683669a314ebb7ff0cf2d68a'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.21297'}]
tags: ["Has Code"]
short_authors: Liu et al.
---
Advancing code reasoning in large language models (LLMs) is fundamentally limited by the scarcity of high-difficulty datasets, especially those with verifiable input-output test cases necessary for rigorous solution validation at scale. We introduce rStar-Coder, which significantly improves LLM code reasoning capabilities by constructing a large-scale, verified dataset of 418K competition-level code problems, 580K long-reasoning solutions along with rich test cases of varying difficulty. This is achieved through three core contributions: (1) we curate competitive programming code problems and oracle solutions to synthesize new, solvable problems; (2) we introduce a reliable input-output test case synthesis pipeline that decouples the generation into a three-step input generation method and a mutual verification mechanism for effective output labeling; (3) we augment problems with high-quality, test-case-verified long-reasoning solutions. Extensive experiments on Qwen models (1.5B-14B) across various code reasoning benchmarks demonstrate the superiority of rStar-Coder dataset, achieving leading performance comparable to frontier reasoning LLMs with much smaller model sizes. On LiveCodeBench, rStar-Coder improves Qwen2.5-7B from 17.4% to an impressive 57.3%, and Qwen2.5-14B from 23.3% to 62.5%, surpassing o3-mini (low) by3.1%. On the more challenging USA Computing Olympiad, our 7B model achieves an average pass@1 accuracy of 16.15%, outperforming the frontier-level QWQ-32B. Code and the dataset will be released at https://github.com/microsoft/rStar.

https://huggingface.co/discussions/paper/683669a314ebb7ff0cf2d68a