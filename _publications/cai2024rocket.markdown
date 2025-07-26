---
layout: publication
title: 'ROCKET-1: Master Open-world Interaction With Visual-temporal Context Prompting'
authors: Shaofei Cai, Zihao Wang, Kewei Lian, Zhancun Mu, Xiaojian Ma, Anji Liu, Yitao
  Liang
conference: No Venue
year: 2024
bibkey: cai2024rocket
additional_links: [{name: Code, url: 'https://craftjarvis.github.io/ROCKET-1'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6719e7db4dfd79aa9f3f6d18'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.17856'}]
tags: ["Prompting"]
short_authors: Cai et al.
---
Vision-language models (VLMs) have excelled in multimodal tasks, but adapting them to embodied decision-making in open-world environments presents challenges. A key issue is the difficulty in smoothly connecting individual entities in low-level observations with abstract concepts required for planning. A common approach to address this problem is through the use of hierarchical agents, where VLMs serve as high-level reasoners that break down tasks into executable sub-tasks, typically specified using language and imagined observations. However, language often fails to effectively convey spatial information, while generating future images with sufficient accuracy remains challenging. To address these limitations, we propose visual-temporal context prompting, a novel communication protocol between VLMs and policy models. This protocol leverages object segmentation from both past and present observations to guide policy-environment interactions. Using this approach, we train ROCKET-1, a low-level policy that predicts actions based on concatenated visual observations and segmentation masks, with real-time object tracking provided by SAM-2. Our method unlocks the full potential of VLMs visual-language reasoning abilities, enabling them to solve complex creative tasks, especially those heavily reliant on spatial understanding. Experiments in Minecraft demonstrate that our approach allows agents to accomplish previously unattainable tasks, highlighting the effectiveness of visual-temporal context prompting in embodied decision-making. Codes and demos will be available on the project page: https://craftjarvis.github.io/ROCKET-1.

https://huggingface.co/discussions/paper/6719e7db4dfd79aa9f3f6d18