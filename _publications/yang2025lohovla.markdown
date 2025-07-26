---
layout: publication
title: 'Lohovla: A Unified Vision-language-action Model For Long-horizon Embodied
  Tasks'
authors: Yi Yang, Jiaxuan Sun, Siqi Kou, Yihan Wang, Zhijie Deng
conference: No Venue
year: 2025
bibkey: yang2025lohovla
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.00411'}]
tags: ["Datasets", "Tools"]
short_authors: Yang et al.
---
Real-world embodied agents face long-horizon tasks, characterized by high-level goals demanding multi-step solutions beyond single actions. Successfully navigating these requires both high-level task planning (i.e., decomposing goals into sub-tasks) and low-level motion control (i.e., generating precise robot actions). While existing vision language action (VLA) models and hierarchical architectures offer potential in embodied tasks, the former often falter in planning, and the latter can suffer from coordination issues, both hampering performance. We introduce a new unified VLA framework for long-horizon tasks, dubbed LoHoVLA, to overcome these limitations. LoHoVLA leverages a large pretrained vision language model (VLM) as the backbone to jointly generate language and action tokens for sub-task generation and robot action prediction, respectively. This shared representation promotes better generalization across tasks. Additionally, LoHoVLA embraces a hierarchical closed-loop control mechanism to mitigate errors originating from both high-level planning and low-level control. To train LoHoVLA, we introduce LoHoSet, a dataset built on the Ravens simulator, containing 20 long-horizon tasks, each with 1,000 expert demonstrations composed of visual observations, linguistic goals, sub-tasks, and robot actions. Experimental results show that LoHoVLA significantly surpasses both hierarchical and standard VLA approaches on long-horizon embodied tasks in the Ravens simulator. These findings underscore the promise of unified architectures for advancing generalizable embodied intelligence.

https://huggingface.co/discussions/paper/683e86e31bca54bb6d169ff5