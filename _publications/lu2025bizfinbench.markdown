---
layout: publication
title: 'Bizfinbench: A Business-driven Real-world Financial Benchmark For Evaluating
  Llms'
authors: Guilong Lu, Xuntao Guo, Rongjunchen Zhang, Wenqiao Zhu, Ji Liu
conference: No Venue
year: 2025
bibkey: lu2025bizfinbench
additional_links: [{name: Code, url: 'https://github.com/HiThink-Research/BizFinBench'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/683536f170d215849adfc35e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.19457'}]
tags: ["Applications", "Evaluation"]
short_authors: Lu et al.
---
Large language models excel in general tasks, yet assessing their reliability in logic-heavy, precision-critical domains like finance, law, and healthcare remains challenging. To address this, we introduce BizFinBench, the first benchmark specifically designed to evaluate LLMs in real-world financial applications. BizFinBench consists of 6,781 well-annotated queries in Chinese, spanning five dimensions: numerical calculation, reasoning, information extraction, prediction recognition, and knowledge-based question answering, grouped into nine fine-grained categories. The benchmark includes both objective and subjective metrics. We also introduce IteraJudge, a novel LLM evaluation method that reduces bias when LLMs serve as evaluators in objective metrics. We benchmark 25 models, including both proprietary and open-source systems. Extensive experiments show that no model dominates across all tasks. Our evaluation reveals distinct capability patterns: (1) In Numerical Calculation, Claude-3.5-Sonnet (63.18) and DeepSeek-R1 (64.04) lead, while smaller models like Qwen2.5-VL-3B (15.92) lag significantly; (2) In Reasoning, proprietary models dominate (ChatGPT-o3: 83.58, Gemini-2.0-Flash: 81.15), with open-source models trailing by up to 19.49 points; (3) In Information Extraction, the performance spread is the largest, with DeepSeek-R1 scoring 71.46, while Qwen3-1.7B scores 11.23; (4) In Prediction Recognition, performance variance is minimal, with top models scoring between 39.16 and 50.00. We find that while current LLMs handle routine finance queries competently, they struggle with complex scenarios requiring cross-concept reasoning. BizFinBench offers a rigorous, business-aligned benchmark for future research. The code and dataset are available at https://github.com/HiThink-Research/BizFinBench.

https://huggingface.co/discussions/paper/683536f170d215849adfc35e