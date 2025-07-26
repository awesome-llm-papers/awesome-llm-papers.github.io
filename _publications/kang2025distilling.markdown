---
layout: publication
title: Distilling LLM Agent Into Small Models With Retrieval And Code Tools
authors: Minki Kang, Jongwon Jeong, Seanie Lee, Jaewoong Cho, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: kang2025distilling
additional_links: [{name: Code, url: 'https://github.com/Nardien/agent-distillation'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6833ca00298a7bec9c3da444'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.17612'}]
tags: ["Agentic", "Efficiency", "Has Code", "Tools"]
short_authors: Kang et al.
---
Large language models (LLMs) excel at complex reasoning tasks but remain computationally expensive, limiting their practical deployment. To address this, recent works have focused on distilling reasoning capabilities into smaller language models (sLMs) using chain-of-thought (CoT) traces from teacher LLMs. However, this approach struggles in scenarios requiring rare factual knowledge or precise computation, where sLMs often hallucinate due to limited capability. In this work, we propose Agent Distillation, a framework for transferring not only reasoning capability but full task-solving behavior from LLM-based agents into sLMs with retrieval and code tools. We improve agent distillation along two complementary axes: (1) we introduce a prompting method called first-thought prefix to enhance the quality of teacher-generated trajectories; and (2) we propose a self-consistent action generation for improving test-time robustness of small agents. We evaluate our method on eight reasoning tasks across factual and mathematical domains, covering both in-domain and out-of-domain generalization. Our results show that sLMs as small as 0.5B, 1.5B, 3B parameters can achieve performance competitive with next-tier larger 1.5B, 3B, 7B models fine-tuned using CoT distillation, demonstrating the potential of agent distillation for building practical, tool-using small agents. Our code is available at https://github.com/Nardien/agent-distillation.

https://huggingface.co/discussions/paper/6833ca00298a7bec9c3da444