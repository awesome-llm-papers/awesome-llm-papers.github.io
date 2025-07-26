---
layout: publication
title: Video Action Differencing
authors: James Burgess, Xiaohan Wang, Yuhui Zhang, Anita Rau, Alejandro Lozano, Lisa
  Dunlap, Trevor Darrell, Serena Yeung-levy
conference: No Venue
year: 2025
bibkey: burgess2025video
additional_links: [{name: Code, url: 'https://huggingface.co/datasets/jmhb/VidDiffBench'},
  {name: Code, url: 'http://jmhb0.github.io/viddiff'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67d0e917d0038007e5a751e9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.07860'}]
tags: ["Agentic", "Applications", "Datasets", "Evaluation", "Has Code", "Model Architecture"]
short_authors: Burgess et al.
---
How do two individuals differ when performing the same action? In this work, we introduce Video Action Differencing (VidDiff), the novel task of identifying subtle differences between videos of the same action, which has many applications, such as coaching and skill learning. To enable development on this new task, we first create VidDiffBench, a benchmark dataset containing 549 video pairs, with human annotations of 4,469 fine-grained action differences and 2,075 localization timestamps indicating where these differences occur. Our experiments demonstrate that VidDiffBench poses a significant challenge for state-of-the-art large multimodal models (LMMs), such as GPT-4o and Qwen2-VL. By analyzing failure cases of LMMs on VidDiffBench, we highlight two key challenges for this task: localizing relevant sub-actions over two videos and fine-grained frame comparison. To overcome these, we propose the VidDiff method, an agentic workflow that breaks the task into three stages: action difference proposal, keyframe localization, and frame differencing, each stage utilizing specialized foundation models. To encourage future research in this new task, we release the benchmark at https://huggingface.co/datasets/jmhb/VidDiffBench and code at http://jmhb0.github.io/viddiff.

https://huggingface.co/discussions/paper/67d0e917d0038007e5a751e9