---
layout: publication
title: 'Jarvisart: Liberating Human Artistic Creativity Via An Intelligent Photo Retouching
  Agent'
authors: Yunlong Lin, Zixu Lin, Kunjie Lin, Jinbin Bai, Panwang Pan, Chenxin Li, Haoyu
  Chen, Zhongdao Wang, Xinghao Ding, Wenbo Li, Shuicheng Yan
conference: No Venue
year: 2025
bibkey: lin2025jarvisart
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.17612'}]
tags: ["Tools"]
short_authors: Lin et al.
---
Photo retouching has become integral to contemporary visual storytelling, enabling users to capture aesthetics and express creativity. While professional tools such as Adobe Lightroom offer powerful capabilities, they demand substantial expertise and manual effort. In contrast, existing AI-based solutions provide automation but often suffer from limited adjustability and poor generalization, failing to meet diverse and personalized editing needs. To bridge this gap, we introduce JarvisArt, a multi-modal large language model (MLLM)-driven agent that understands user intent, mimics the reasoning process of professional artists, and intelligently coordinates over 200 retouching tools within Lightroom. JarvisArt undergoes a two-stage training process: an initial Chain-of-Thought supervised fine-tuning to establish basic reasoning and tool-use skills, followed by Group Relative Policy Optimization for Retouching (GRPO-R) to further enhance its decision-making and tool proficiency. We also propose the Agent-to-Lightroom Protocol to facilitate seamless integration with Lightroom. To evaluate performance, we develop MMArt-Bench, a novel benchmark constructed from real-world user edits. JarvisArt demonstrates user-friendly interaction, superior generalization, and fine-grained control over both global and local adjustments, paving a new avenue for intelligent photo retouching. Notably, it outperforms GPT-4o with a 60% improvement in average pixel-level metrics on MMArt-Bench for content fidelity, while maintaining comparable instruction-following capabilities. Project Page: https://jarvisart.vercel.app/.

https://huggingface.co/discussions/paper/685b7539d2ee4fac76521e6e