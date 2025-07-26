---
layout: publication
title: 'Preference Leakage: A Contamination Problem In Llm-as-a-judge'
authors: Dawei Li, Renliang Sun, Yue Huang, Ming Zhong, Bohan Jiang, Jiawei Han, Xiangliang
  Zhang, Wei Wang, Huan Liu
conference: No Venue
year: 2025
bibkey: li2025preference
additional_links: [{name: Code, url: 'https://github.com/David-Li0406/Preference-Leakage'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67a1ad78d797fac51fa807c1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.01534'}]
tags: ["Ethics & Fairness"]
short_authors: Li et al.
---
Large Language Models (LLMs) as judges and LLM-based data synthesis have emerged as two fundamental LLM-driven data annotation methods in model development. While their combination significantly enhances the efficiency of model training and evaluation, little attention has been given to the potential contamination brought by this new model development paradigm. In this work, we expose preference leakage, a contamination problem in LLM-as-a-judge caused by the relatedness between the synthetic data generators and LLM-based evaluators. To study this issue, we first define three common relatednesses between data generator LLM and judge LLM: being the same model, having an inheritance relationship, and belonging to the same model family. Through extensive experiments, we empirically confirm the bias of judges towards their related student models caused by preference leakage across multiple LLM baselines and benchmarks. Further analysis suggests that preference leakage is a pervasive issue that is harder to detect compared to previously identified biases in LLM-as-a-judge scenarios. All of these findings imply that preference leakage is a widespread and challenging problem in the area of LLM-as-a-judge. We release all codes and data at: https://github.com/David-Li0406/Preference-Leakage.

https://huggingface.co/discussions/paper/67a1ad78d797fac51fa807c1