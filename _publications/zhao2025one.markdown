---
layout: publication
title: One Token To Fool Llm-as-a-judge
authors: Yulai Zhao, Haolin Liu, Dian Yu, S. Y. Kung, Haitao Mi, Dong Yu
conference: No Venue
year: 2025
bibkey: zhao2025one
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.08794'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Prompting", "Reinforcement Learning", "Security", "Training Techniques"]
short_authors: Zhao et al.
---
Generative reward models (also known as LLMs-as-judges), which use large language models (LLMs) to evaluate answer quality, are increasingly adopted in reinforcement learning with verifiable rewards (RLVR). They are often preferred over rigid rule-based metrics, especially for complex reasoning tasks involving free-form outputs. In this paradigm, an LLM is typically prompted to compare a candidate answer against a ground-truth reference and assign a binary reward indicating correctness. Despite the seeming simplicity of this comparison task, we find that generative reward models exhibit surprising vulnerabilities to superficial manipulations: non-word symbols (e.g., ":" or ".") or reasoning openers like "Thought process:" and "Let's solve this problem step by step." can often lead to false positive rewards. We demonstrate that this weakness is widespread across LLMs, datasets, and prompt formats, posing a serious threat for core algorithmic paradigms that rely on generative reward models, such as rejection sampling, preference optimization, and RLVR. To mitigate this issue, we introduce a simple yet effective data augmentation strategy and train a new generative reward model with substantially improved robustness. Our findings highlight the urgent need for more reliable LLM-based evaluation methods. We release our robust, general-domain reward model and its synthetic training data at https://huggingface.co/sarosavo/Master-RM and https://huggingface.co/datasets/sarosavo/Master-RM.

https://huggingface.co/discussions/paper/68747a58257d4f04353702ff