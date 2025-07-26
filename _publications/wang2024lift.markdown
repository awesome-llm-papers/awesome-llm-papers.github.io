---
layout: publication
title: 'Lift: Leveraging Human Feedback For Text-to-video Model Alignment'
authors: Yibin Wang, Zhiyu Tan, Junyan Wang, Xiaomeng Yang, Cheng Jin, Hao Li
conference: No Venue
year: 2024
bibkey: wang2024lift
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.04814'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Reinforcement Learning"]
short_authors: Wang et al.
---
Recent advancements in text-to-video (T2V) generative models have shown impressive capabilities. However, these models are still inadequate in aligning synthesized videos with human preferences (e.g., accurately reflecting text descriptions), which is particularly difficult to address, as human preferences are inherently subjective and challenging to formalize as objective functions. Therefore, this paper proposes LiFT, a novel fine-tuning method leveraging human feedback for T2V model alignment. Specifically, we first construct a Human Rating Annotation dataset, LiFT-HRA, consisting of approximately 10k human annotations, each including a score and its corresponding rationale. Based on this, we train a reward model LiFT-Critic to learn reward function effectively, which serves as a proxy for human judgment, measuring the alignment between given videos and human expectations. Lastly, we leverage the learned reward function to align the T2V model by maximizing the reward-weighted likelihood. As a case study, we apply our pipeline to CogVideoX-2B, showing that the fine-tuned model outperforms the CogVideoX-5B across all 16 metrics, highlighting the potential of human feedback in improving the alignment and quality of synthesized videos.

https://huggingface.co/discussions/paper/67564cdeee0958ae76fa7471