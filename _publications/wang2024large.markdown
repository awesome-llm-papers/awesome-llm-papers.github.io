---
layout: publication
title: 'Large Action Models: From Inception To Implementation'
authors: Lu Wang, Fangkai Yang, Chaoyun Zhang, Junting Lu, Jiaxu Qian, Shilin He,
  Pu Zhao, Bo Qiao, Ray Huang, Si Qin, Qisheng Su, Jiayi Ye, Yudi Zhang, Jian-guang
  Lou, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang
conference: No Venue
year: 2024
bibkey: wang2024large
additional_links: [{name: Code, url: 'https://github.com/microsoft/UFO/tree/main/dataflow,'},
  {name: Code, url: 'https://microsoft.github.io/UFO/dataflow/overview/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/675f9dcf5dca7e3c5c1f0a47'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2412.10047'}]
tags: ["Agentic", "Applications", "Datasets", "Evaluation", "Has Code", "Tools", "Training Techniques"]
short_authors: Wang et al.
---
As AI continues to advance, there is a growing demand for systems that go beyond language-based assistance and move toward intelligent agents capable of performing real-world actions. This evolution requires the transition from traditional Large Language Models (LLMs), which excel at generating textual responses, to Large Action Models (LAMs), designed for action generation and execution within dynamic environments. Enabled by agent systems, LAMs hold the potential to transform AI from passive language understanding to active task completion, marking a significant milestone in the progression toward artificial general intelligence. In this paper, we present a comprehensive framework for developing LAMs, offering a systematic approach to their creation, from inception to deployment. We begin with an overview of LAMs, highlighting their unique characteristics and delineating their differences from LLMs. Using a Windows OS-based agent as a case study, we provide a detailed, step-by-step guide on the key stages of LAM development, including data collection, model training, environment integration, grounding, and evaluation. This generalizable workflow can serve as a blueprint for creating functional LAMs in various application domains. We conclude by identifying the current limitations of LAMs and discussing directions for future research and industrial deployment, emphasizing the challenges and opportunities that lie ahead in realizing the full potential of LAMs in real-world applications. The code for the data collection process utilized in this paper is publicly available at: https://github.com/microsoft/UFO/tree/main/dataflow, and comprehensive documentation can be found at https://microsoft.github.io/UFO/dataflow/overview/.

https://huggingface.co/discussions/paper/675f9dcf5dca7e3c5c1f0a47