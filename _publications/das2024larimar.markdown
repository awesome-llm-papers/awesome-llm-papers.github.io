---
layout: publication
title: 'Larimar: Large Language Models With Episodic Memory Control'
authors: "Payel Das, Subhajit Chaudhury, Elliot Nelson, Igor Melnyk, Sarath Swaminathan,\
  \ Sihui Dai, Aur\xE9lie Lozano, Georgios Kollias, Vijil Chenthamarakshan, Ji\u0159\
  \xED, Navr\xE1til, Soham Dan, Pin-yu Chen"
conference: No Venue
year: 2024
bibkey: das2024larimar
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.11901'}]
tags: ["Memory & Context", "Model Architecture"]
short_authors: Das et al.
---
Efficient and accurate updating of knowledge stored in Large Language Models (LLMs) is one of the most pressing research challenges today. This paper presents Larimar - a novel, brain-inspired architecture for enhancing LLMs with a distributed episodic memory. Larimar's memory allows for dynamic, one-shot updates of knowledge without the need for computationally expensive re-training or fine-tuning. Experimental results on multiple fact editing benchmarks demonstrate that Larimar attains accuracy comparable to most competitive baselines, even in the challenging sequential editing setup, but also excels in speed - yielding speed-ups of 4-10x depending on the base LLM - as well as flexibility due to the proposed architecture being simple, LLM-agnostic, and hence general. We further provide mechanisms for selective fact forgetting and input context length generalization with Larimar and show their effectiveness.

https://huggingface.co/discussions/paper/65f9194c9622bdda62c68fae