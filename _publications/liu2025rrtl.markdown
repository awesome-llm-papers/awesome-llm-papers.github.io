---
layout: publication
title: 'RRTL: Red Teaming Reasoning Large Language Models In Tool Learning'
authors: Liu Yifei, Cui Yu, Zhang Haibin
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: liu2025rrtl
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.17106'}]
tags: [Datasets, EMNLP, Prompting, Tools, Evaluation, Reinforcement Learning, Security,
  Responsible AI, Merging]
---
While tool learning significantly enhances the capabilities of large language models (LLMs), it also introduces substantial security risks. Prior research has revealed various vulnerabilities in traditional LLMs during tool learning. However, the safety of newly emerging reasoning LLMs (RLLMs), such as DeepSeek-R1, in the context of tool learning remains underexplored. To bridge this gap, we propose RRTL, a red teaming approach specifically designed to evaluate RLLMs in tool learning. It integrates two novel strategies: (1) the identification of deceptive threats, which evaluates the model's behavior in concealing the usage of unsafe tools and their potential risks; and (2) the use of Chain-of-Thought (CoT) prompting to force tool invocation. Our approach also includes a benchmark for traditional LLMs. We conduct a comprehensive evaluation on seven mainstream RLLMs and uncover three key findings: (1) RLLMs generally achieve stronger safety performance than traditional LLMs, yet substantial safety disparities persist across models; (2) RLLMs can pose serious deceptive risks by frequently failing to disclose tool usage and to warn users of potential tool output risks; (3) CoT prompting reveals multi-lingual safety vulnerabilities in RLLMs. Our work provides important insights into enhancing the security of RLLMs in tool learning.