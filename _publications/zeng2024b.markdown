---
layout: publication
title: 'B-star: Monitoring And Balancing Exploration And Exploitation In Self-taught
  Reasoners'
authors: Weihao Zeng, Yuzhen Huang, Lulu Zhao, Yijun Wang, Zifei Shan, Junxian He
conference: No Venue
year: 2024
bibkey: zeng2024b
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.17256'}]
tags: ["Training Techniques"]
short_authors: Zeng et al.
---
In the absence of extensive human-annotated data for complex reasoning tasks, self-improvement -- where models are trained on their own outputs -- has emerged as a primary method for enhancing performance. However, the critical factors underlying the mechanism of these iterative self-improving methods remain poorly understood, such as under what conditions self-improvement is effective, and what are the bottlenecks in the current iterations. In this work, we identify and propose methods to monitor two pivotal factors in this iterative process: (1) the model's ability to generate sufficiently diverse responses (exploration); and (2) the effectiveness of external rewards in distinguishing high-quality candidates from lower-quality ones (exploitation). Using mathematical reasoning as a case study, we begin with a quantitative analysis to track the dynamics of exploration and exploitation, discovering that a model's exploratory capabilities rapidly deteriorate over iterations, and the effectiveness of exploiting external rewards diminishes as well. Motivated by these findings, we introduce B-STaR, a Self-Taught Reasoning framework that autonomously adjusts configurations across iterations to Balance exploration and exploitation, thereby optimizing the self-improving effectiveness based on the current policy model and available rewards. Our experiments on mathematical reasoning, coding, and commonsense reasoning demonstrate that B-STaR not only enhances the model's exploratory capabilities throughout training but also achieves a more effective balance between exploration and exploitation, leading to superior performance.

https://huggingface.co/discussions/paper/676a23c29fc612bf4a3b943b