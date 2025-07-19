---
layout: publication
title: Adversarial Training Of Reward Models
authors: Bukharin et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: bukharin2025adversarial
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.06141'}]
tags: [RAG, ICCV, Training Techniques, Agentic, Tools, Reinforcement Learning, Security]
---
Reward modeling has emerged as a promising approach for the scalable
alignment of language models. However, contemporary reward models (RMs) often
lack robustness, awarding high rewards to low-quality, out-of-distribution
(OOD) samples. This can lead to reward hacking, where policies exploit
unintended shortcuts to maximize rewards, undermining alignment. To address
this challenge, we introduce Adv-RM, a novel adversarial training framework
that automatically identifies adversarial examples -- responses that receive
high rewards from the target RM but are OOD and of low quality. By leveraging
reinforcement learning, Adv-RM trains a policy to generate adversarial examples
that reliably expose vulnerabilities in large state-of-the-art reward models
such as Nemotron 340B RM. Incorporating these adversarial examples into the
reward training process improves the robustness of RMs, mitigating reward
hacking and enhancing downstream performance in RLHF. We demonstrate that
Adv-RM significantly outperforms conventional RM training, increasing stability
and enabling more effective RLHF training in both synthetic and real-data
settings.