---
layout: publication
title: 'Deepresearch Bench: A Comprehensive Benchmark For Deep Research Agents'
authors: Mingxuan Du, Benfeng Xu, Chiwei Zhu, Xiaorui Wang, Zhendong Mao
conference: No Venue
year: 2025
bibkey: du2025deepresearch
additional_links: [{name: Code, url: 'https://github.com/Ayanami0730/deep_research_bench'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/684ff5051d9b438aa3957a84'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.11763'}]
tags: ["Evaluation", "Has Code", "Tools"]
short_authors: Du et al.
---
Deep Research Agents are a prominent category of LLM-based agents. By autonomously orchestrating multistep web exploration, targeted retrieval, and higher-order synthesis, they transform vast amounts of online information into analyst-grade, citation-rich reports--compressing hours of manual desk research into minutes. However, a comprehensive benchmark for systematically evaluating the capabilities of these agents remains absent. To bridge this gap, we present DeepResearch Bench, a benchmark consisting of 100 PhD-level research tasks, each meticulously crafted by domain experts across 22 distinct fields. Evaluating DRAs is inherently complex and labor-intensive. We therefore propose two novel methodologies that achieve strong alignment with human judgment. The first is a reference-based method with adaptive criteria to assess the quality of generated research reports. The other framework is introduced to evaluate DRA's information retrieval and collection capabilities by assessing its effective citation count and overall citation accuracy. We have open-sourced DeepResearch Bench and key components of these frameworks at https://github.com/Ayanami0730/deep_research_bench to accelerate the development of practical LLM-based agents.

https://huggingface.co/discussions/paper/684ff5051d9b438aa3957a84