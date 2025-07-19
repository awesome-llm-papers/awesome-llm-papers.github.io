---
layout: publication
title: Patience Is The Key To Large Language Model Reasoning
authors: Yu Yijiong
conference: JAMA Network Open
year: 2024
bibkey: yu2024patience
citations: 163
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.13082'}]
tags: [RAG, Training Techniques, Efficiency And Optimization, Reinforcement Learning,
  Datasets]
---
Recent advancements in the field of large language models, particularly
through the Chain of Thought (CoT) approach, have demonstrated significant
improvements in solving complex problems. However, existing models either tend
to sacrifice detailed reasoning for brevity due to user preferences, or require
extensive and expensive training data to learn complicated reasoning ability,
limiting their potential in solving complex tasks. To bridge this gap,
following the concept of scaling test-time, we propose a simple method by
encouraging models to adopt a more patient reasoning style without the need of
introducing new knowledge or skills. To employ a preference optimization
approach, we generate detailed reasoning processes as positive examples and
simple answers as negative examples, thereby training the model to favor
thoroughness in its responses. Our results demonstrate a performance increase
of up to 2.1% on GSM8k with training just on a lightweight dataset.