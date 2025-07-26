---
layout: publication
title: 'Web-shepherd: Advancing Prms For Reinforcing Web Agents'
authors: Hyungjoo Chae, Sunghwan Kim, Junhee Cho, Seungone Kim, Seungjun Moon, Gyeom
  Hwangbo, Dongha Lim, Minjin Kim, Yeonjun Hwang, Minju Gwak, Dongwook Choi, Minseok
  Kang, Gwanhoon Im, Byeongung Cho, Hyojun Kim, Jun Hee Han, Taeyoon Kwon, Minju Kim,
  Beong-woo Kwak, Dongjin Kang, Jinyoung Yeo
conference: No Venue
year: 2025
bibkey: chae2025web
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/682e854951706f69070acbf0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.15277'}]
tags: ["Reinforcement Learning"]
short_authors: Chae et al.
---
Web navigation is a unique domain that can automate many repetitive real-life tasks and is challenging as it requires long-horizon sequential decision making beyond typical multimodal large language model (MLLM) tasks. Yet, specialized reward models for web navigation that can be utilized during both training and test-time have been absent until now. Despite the importance of speed and cost-effectiveness, prior works have utilized MLLMs as reward models, which poses significant constraints for real-world deployment. To address this, in this work, we propose the first process reward model (PRM) called Web-Shepherd which could assess web navigation trajectories in a step-level. To achieve this, we first construct the WebPRM Collection, a large-scale dataset with 40K step-level preference pairs and annotated checklists spanning diverse domains and difficulty levels. Next, we also introduce the WebRewardBench, the first meta-evaluation benchmark for evaluating PRMs. In our experiments, we observe that our Web-Shepherd achieves about 30 points better accuracy compared to using GPT-4o on WebRewardBench. Furthermore, when testing on WebArena-lite by using GPT-4o-mini as the policy and Web-Shepherd as the verifier, we achieve 10.9 points better performance, in 10 less cost compared to using GPT-4o-mini as the verifier. Our model, dataset, and code are publicly available at LINK.

https://huggingface.co/discussions/paper/682e854951706f69070acbf0