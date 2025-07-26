---
layout: publication
title: 'Deepperception: Advancing R1-like Cognitive Visual Perception In Mllms For
  Knowledge-intensive Visual Grounding'
authors: Xinyu Ma, Ziyang Ding, Zhicong Luo, Chi Chen, Zonghao Guo, Derek F. Wong,
  Xiaoyi Feng, Maosong Sun
conference: No Venue
year: 2025
bibkey: ma2025deepperception
additional_links: [{name: Code, url: 'https://github.com/thunlp/DeepPerception'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67da2c85aa2c34f7d95e4796'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.12797'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Has Code", "Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Ma et al.
---
Human experts excel at fine-grained visual discrimination by leveraging domain knowledge to refine perceptual features, a capability that remains underdeveloped in current Multimodal Large Language Models (MLLMs). Despite possessing vast expert-level knowledge, MLLMs struggle to integrate reasoning into visual perception, often generating direct responses without deeper analysis. To bridge this gap, we introduce knowledge-intensive visual grounding (KVG), a novel visual grounding task that requires both fine-grained perception and domain-specific knowledge integration. To address the challenges of KVG, we propose DeepPerception, an MLLM enhanced with cognitive visual perception capabilities. Our approach consists of (1) an automated data synthesis pipeline that generates high-quality, knowledge-aligned training samples, and (2) a two-stage training framework combining supervised fine-tuning for cognitive reasoning scaffolding and reinforcement learning to optimize perception-cognition synergy. To benchmark performance, we introduce KVG-Bench a comprehensive dataset spanning 10 domains with 1.3K manually curated test cases. Experimental results demonstrate that DeepPerception significantly outperforms direct fine-tuning, achieving +8.08% accuracy improvements on KVG-Bench and exhibiting +4.60% superior cross-domain generalization over baseline approaches. Our findings highlight the importance of integrating cognitive processes into MLLMs for human-like visual perception and open new directions for multimodal reasoning research. The data, codes, and models are released at https://github.com/thunlp/DeepPerception.

https://huggingface.co/discussions/paper/67da2c85aa2c34f7d95e4796