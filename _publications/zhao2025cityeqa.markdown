---
layout: publication
title: 'Cityeqa: A Hierarchical LLM Agent On Embodied Question Answering Benchmark
  In City Space'
authors: Zhao et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2025
bibkey: zhao2025cityeqa
citations: 145
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.12532'}]
tags: [Agentic, Evaluation, CVPR, Reinforcement Learning, Fine Tuning, Datasets]
---
Embodied Question Answering (EQA) has primarily focused on indoor environments, leaving the complexities of urban settings-spanning environment, action, and perception-largely unexplored. To bridge this gap, we introduce CityEQA, a new task where an embodied agent answers open-vocabulary questions through active exploration in dynamic city spaces. To support this task, we present CityEQA-EC, the first benchmark dataset featuring 1,412 human-annotated tasks across six categories, grounded in a realistic 3D urban simulator. Moreover, we propose Planner-Manager-Actor (PMA), a novel agent tailored for CityEQA. PMA enables long-horizon planning and hierarchical task execution: the Planner breaks down the question answering into sub-tasks, the Manager maintains an object-centric cognitive map for spatial reasoning during the process control, and the specialized Actors handle navigation, exploration, and collection sub-tasks. Experiments demonstrate that PMA achieves 60.7% of human-level answering accuracy, significantly outperforming competitive baselines. While promising, the performance gap compared to humans highlights the need for enhanced visual reasoning in CityEQA. This work paves the way for future advancements in urban spatial intelligence. Dataset and code are available at https://github.com/BiluYong/CityEQA.git.