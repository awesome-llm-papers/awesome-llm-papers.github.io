---
layout: publication
title: 'Spacer: Reinforcing Mllms In Video Spatial Reasoning'
authors: Ouyang et al.
conference: IEEE Transactions on Image Processing
year: 2025
bibkey: ouyang2025spacer
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.01805'}]
tags: [RAG, Training Techniques, GPT, Agentic, Tools, Evaluation, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, Multimodal Models, Datasets]
---
Video spatial reasoning, which involves inferring the underlying spatial structure from observed video frames, poses a significant challenge for existing Multimodal Large Language Models (MLLMs). This limitation stems primarily from 1) the absence of high-quality datasets for this task, and 2) the lack of effective training strategies to develop spatial reasoning capabilities. Motivated by the success of Reinforcement Learning with Verifiable Reward (RLVR) in unlocking LLM reasoning abilities, this work aims to improve MLLMs in video spatial reasoning through the RLVR paradigm. To this end, we introduce the \\(\textbf\{SpaceR\}\\) framework. First, we present \\(\textbf\{SpaceR-151k\}\\), a dataset with 91k questions spanning diverse spatial reasoning scenarios with verifiable answers, and 60k samples for maintaining general multimodal understanding. Second, we propose \\(\textbf\{Spatially-Guided RLVR (SG-RLVR)\}\\), a novel reinforcement learning approach that extends Group Relative Policy Optimization (GRPO) with a novel map imagination mechanism, which encourages the model to infer spatial layouts in the thinking process, thereby facilitating more effective spatial reasoning. Extensive experiments demonstrate that SpaceR achieves state-of-the-art performance on spatial reasoning benchmarks (e.g., VSI-Bench, STI-Bench, and SPAR-Bench), while maintaining competitive results on video understanding benchmarks (e.g., Video-MME, TempCompass, and LongVideoBench). Remarkably, SpaceR surpasses the advanced GPT-4o by 11.6% accuracy on VSI-Bench and is on par with the leading proprietary model Gemini-2.0-Flash, highlighting the effectiveness of our SpaceR-151k dataset and SG-RLVR in reinforcing spatial reasoning ability of MLLMs. Code, model, and dataset are available at https://github.com/OuyangKun10/SpaceR.