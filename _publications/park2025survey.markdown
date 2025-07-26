---
layout: publication
title: 'A Survey On Inference Engines For Large Language Models: Perspectives On Optimization
  And Efficiency'
authors: Sihyeong Park, Sungryeol Jeon, Chaelyn Lee, Seokhun Jeon, Byung-soo Kim,
  Jemin Lee
conference: No Venue
year: 2025
bibkey: park2025survey
additional_links: [{name: Code, url: 'https://github.com/sihyeong/Awesome-LLM-Inference-Engine'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6819950cd55db085708dd32a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.01658'}]
tags: ["Survey Paper"]
short_authors: Park et al.
---
Large language models (LLMs) are widely applied in chatbots, code generators, and search engines. Workloads such as chain-of-thought, complex reasoning, and agent services significantly increase the inference cost by invoking the model repeatedly. Optimization methods such as parallelism, compression, and caching have been adopted to reduce costs, but the diverse service requirements make it hard to select the right method. Recently, specialized LLM inference engines have emerged as a key component for integrating the optimization methods into service-oriented infrastructures. However, a systematic study on inference engines is still lacking. This paper provides a comprehensive evaluation of 25 open-source and commercial inference engines. We examine each inference engine in terms of ease-of-use, ease-of-deployment, general-purpose support, scalability, and suitability for throughput- and latency-aware computation. Furthermore, we explore the design goals of each inference engine by investigating the optimization techniques it supports. In addition, we assess the ecosystem maturity of open source inference engines and handle the performance and cost policy of commercial solutions. We outline future research directions that include support for complex LLM-based services, support of various hardware, and enhanced security, offering practical guidance to researchers and developers in selecting and designing optimized LLM inference engines. We also provide a public repository to continually track developments in this fast-evolving field: https://github.com/sihyeong/Awesome-LLM-Inference-Engine

https://huggingface.co/discussions/paper/6819950cd55db085708dd32a