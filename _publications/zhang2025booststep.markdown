---
layout: publication
title: 'Booststep: Boosting Mathematical Capability Of Large Language Models Via Improved
  Single-step Reasoning'
authors: Beichen Zhang, Yuhong Liu, Xiaoyi Dong, Yuhang Zang, Pan Zhang, Haodong Duan,
  Yuhang Cao, Dahua Lin, Jiaqi Wang
conference: No Venue
year: 2025
bibkey: zhang2025booststep
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.03226'}]
tags: ["Model Architecture"]
short_authors: Zhang et al.
---
Cutting-edge large language models (LLMs) demonstrate promising performance in solving complex math problems with a divide-and-conquer pipeline and the assistance of in-context learning (ICL) examples. However, their potential for improvement is limited by two critical problems within their ICL examples: granularity-mismatch and the ensuing negative-effect noise problem. Specifically, the LLMs are capable of the dividing process yet mostly failed by inaccurate reasoning within a few conquer steps, while the ICL examples retrieved in question-grained sometimes lack relevant steps for a specific challenging reasoning step. Further, this disconnect may hinder the correct reasoning due to its irrelevance. To this end, we focus on improving the reasoning quality within each step and present BoostStep. BoostStep aligns the granularity between the retrieving and reasoning on step grained, and provides highly related ICL examples for each reasoning step with a novel `first-try' strategy. BoostStep provides more relevant examples than the coarse question-grained strategy, enhancing the model reasoning quality within each step steadily. BoostStep is a general and robust reasoning-enhancing method that not only improves standalone reasoning performance but also integrates seamlessly with Monte Carlo Tree Search methods (MCTS) to refine both candidate generation and decision-making. Quantitatively, it improves GPT-4o and Qwen2.5-Math-72B by 3.6% and 2.0% respectively on various mathematical benchmarks, and 7.5% gain combined with MCTS.

https://huggingface.co/discussions/paper/677cdcd60604b68871999e7b