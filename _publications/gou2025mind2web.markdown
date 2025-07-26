---
layout: publication
title: 'Mind2web 2: Evaluating Agentic Search With Agent-as-a-judge'
authors: "Boyu Gou, Zanming Huang, Yuting Ning, Yu Gu, Michael Lin, Weijian Qi, Andrei\
  \ Kopanev, Botao Yu, Bernal Jim\xE9nez Guti\xE9rrez, Yiheng Shu, Chan Hee Song,\
  \ Jiaman Wu, Shijie Chen, Hanane Nour Moussa, Tianshu Zhang, Jian Xie, Yifei Li,\
  \ Tianci Xue, Zeyi Liao, Kai Zhang, Boyuan Zheng, Zhaowei Cai, Viktor Rozgic, Morteza\
  \ Ziyadi, Huan Sun, Yu Su"
conference: No Venue
year: 2025
bibkey: gou2025mind2web
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.21506'}]
tags: ["Agentic", "Evaluation"]
short_authors: Gou et al.
---
Agentic search such as Deep Research systems, where large language models autonomously browse the web, synthesize information, and return comprehensive citation-backed answers, represents a major shift in how users interact with web-scale information. While promising greater efficiency and cognitive offloading, the growing complexity and open-endedness of agentic search have outpaced existing evaluation benchmarks and methodologies, which largely assume short search horizons and static answers. In this paper, we introduce Mind2Web 2, a benchmark of 130 realistic, high-quality, and long-horizon tasks that require real-time web browsing and extensive information synthesis, constructed with over 1,000 hours of human labor. To address the challenge of evaluating time-varying and complex answers, we propose a novel Agent-as-a-Judge framework. Our method constructs task-specific judge agents based on a tree-structured rubric design to automatically assess both answer correctness and source attribution. We conduct a comprehensive evaluation of nine frontier agentic search systems and human performance, along with a detailed error analysis to draw insights for future development. The best-performing system, OpenAI Deep Research, can already achieve 50-70% of human performance while spending half the time, showing a great potential. Altogether, Mind2Web 2 provides a rigorous foundation for developing and benchmarking the next generation of agentic search systems.

https://huggingface.co/discussions/paper/685df93d71131fa43be08ab0