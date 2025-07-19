---
layout: publication
title: 'Flex-travelplanner: A Benchmark For Flexible Planning With Language Agents'
authors: Oh Juhyun, Kim Eunsu, Oh Alice
conference: Computer
year: 2025
bibkey: oh2025flex
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.04649'}]
tags: [ICCV, GPT, Agentic, Tools, CVPR, Evaluation, Model Architecture, Reinforcement
    Learning, Datasets]
---
Real-world planning problems require constant adaptation to changing requirements and balancing of competing constraints. However, current benchmarks for evaluating LLMs' planning capabilities primarily focus on static, single-turn scenarios. We introduce Flex-TravelPlanner, a benchmark that evaluates language models' ability to reason flexibly in dynamic planning scenarios. Building on the TravelPlanner dataset~\citep\{xie2024travelplanner\}, we introduce two novel evaluation settings: (1) sequential constraint introduction across multiple turns, and (2) scenarios with explicitly prioritized competing constraints. Our analysis of GPT-4o and Llama 3.1 70B reveals several key findings: models' performance on single-turn tasks poorly predicts their ability to adapt plans across multiple turns; constraint introduction order significantly affects performance; and models struggle with constraint prioritization, often incorrectly favoring newly introduced lower priority preferences over existing higher-priority constraints. These findings highlight the importance of evaluating LLMs in more realistic, dynamic planning scenarios and suggest specific directions for improving model performance on complex planning tasks. The code and dataset for our framework are publicly available at https://github.com/juhyunohh/FlexTravelBench.